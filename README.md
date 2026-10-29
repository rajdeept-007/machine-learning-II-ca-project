# ReCell — Used Smartphone Value Estimator

## Overview
ReCell is a machine learning project that predicts the normalized resale price of used smartphones based on their specifications, usage, and physical condition.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Google Colab

## Machine Learning Algorithms
- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regression
- Random Forest Regression

## Key Features
- Data cleaning and exploratory data analysis
- Comparison of regression models
- Cross-validation and hyperparameter tuning using GridSearchCV
- Model evaluation using MAE, RMSE, and R²
- Feature importance analysis and resale price prediction

## Dataset
The dataset contains 5,454 records and 24 columns, including smartphone specifications, usage information, condition, and normalized prices. It includes both original and synthetic records.

## Objective
To compare regression algorithms and identify a suitable model for estimating used smartphone resale values.

## Limitations
The dataset contains synthetic records, and the target is a normalized price rather than a verified market price in Indian rupees. Results may not reflect real-world resale prices.

## How to Run
1. Open the notebook in Google Colab.
2. Upload `used_device_data.csv`.
3. Run all cells sequentially.
