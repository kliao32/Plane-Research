# Aircraft Survival Analysis

## Overview
This project analyzes how long aircraft remain active using survival analysis.

## Data
aircraft_data.csv

## Methods
- Kaplan-Meier survival curves
- Log-rank test
- Logistic regression

## Results
- Probability of remaining active declines sharply after ~20–25 years  
- Log-rank test shows significant differences between aircraft models (p < 0.05)  
- Logistic regression confirms age is a strong predictor of aircraft retirement

## Visualization

### Logistic Regression
![Logistic](figures/logistic_age_probability.png)

### Model Comparison
![Model](figures/model_comparison1.png)
![Model](figures/model_comparison2.png)
![Model](figures/model_comparison3.png)
![Model](figures/model_comparison4.png)

### ROC Curve
![ROC](figures/random_forest_roc.png)

### Feature Importance
![Feature](figures/random_forest_feature_importance.png)

### Retirement Age Comparison
![Retirement](figures/retirement_age_legacy_vs_lcc.png)


## Files
- Plane.ipynb: main analysis notebook  
- Plane Research Report.pdf: full report  

## Author
Kaitao Liao
