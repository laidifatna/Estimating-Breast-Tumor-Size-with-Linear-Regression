# Estimating-Breast-Tumor-Size-with-Linear-Regression

My second machine-learning project explores whether cell-nucleus measurements and lymph-node status can predict tumor size using the Breast Cancer Wisconsin (Prognostic) dataset.

## Methods
- Data cleaning and exploratory analysis
- Pearson correlation analysis
- Mean baseline and linear regression with all, four selected, and one input variable
- Evaluation using MAE, RMSE, R², five-fold cross-validation, and residual plots

## Results
The full and four-variable models did not perform better as the baseline on the test set. The lymph-node-only model performed best, with MAE of **1.02 cm**, RMSE of **1.31 cm**, and R² of **0.096**, but predictive accuracy remained limited.

## Dataset
[UCI Breast Cancer Wisconsin (Prognostic)](https://doi.org/10.24432/C5GK50), by Wolberg, Street, and Mangasarian (1995). Licensed under CC BY 4.0.

This is an educational project.
