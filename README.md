# Bachelor's Thesis Repository

This repository hosts the complete materials from my bachelor's thesis on **Bayesian Optimization**, focusing on the balance between **exploration** and **exploitation**.

## Thesis Information
- Title: *Analysis of Bayesian Optimization Components in Terms of the Properties of Exploration and Exploitation*
- Degree: Bachelor's
- Field: Mathematics and Data Analysis
- University: Warsaw University of Technology
- Grade: 5

## Overview
**Bayesian Optimization** (BO) is an effective method for optimizing expensive black-box functions, particularly in machine learning applications such as hyperparameter tuning. Its efficiency largely depends on the balance between **exploration** (searching unknown regions) and **exploitation** (focusing on areas known to yield good results).

This thesis investigates how key components of BO - **surrogate models** and **acquisition functions** - affect this exploration-exploitation trade-off. The theoretical part provides an overview of surrogate models such as Gaussian Processes, Random Forests and Extra Trees, as well as acquisition functions including Expected Improvement, Probability of Improvement and Lower Confidence Bound.

## Experiment
- Various combinations of surrogate models and acquisition functions were evaluated across multiple datasets.
- BO performance was compared to traditional methods like Grid Search and Random Search.
- Results were analyzed based on convergence behavior and overall optimization efficiency, using **AUC** and domain-specific metrics such as **ADTM** and **OTSD**.

**Key finding**: Bayesian Optimization consistently outperforms traditional methods, and well-chosen components lead to faster convergence, higher tuning efficiency, and more structured exploration behavior.


## Repository Content
- [Thesis.pdf](Thesis.pdf) - Full thesis document
- [Experiment.ipynb](Experiment.ipynb) - Jupyter Notebook with experiment

