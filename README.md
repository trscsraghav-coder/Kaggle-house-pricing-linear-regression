
# House Price Prediction with Linear Regression

A machine learning project predicting house sale prices using the Kaggle House Prices dataset, built with scikit-learn.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- scikit-learn

## What This Project Does
- Loads and explores the Kaggle House Prices dataset
- Builds an initial linear regression model using a single feature (Lot Area) as a baseline
- Iteratively adds features (Living Area, Overall Quality, Basement Size, Garage Capacity, Year Built) to improve the model
- Evaluates model performance using R² score
- Visualizes predicted vs. actual sale prices with a scatter plot

## Key Findings
- Starting with just Lot Area, the model explained only ~8% of price variation (R² = 0.084)
- Adding Living Area, Overall Quality, Basement Size, Garage Capacity, and Year Built raised R² to about 0.80
- Predictions typically landed within 5–10% of actual sale prices
- Adding 1st Floor Square Footage on top of the other features barely changed R², since it overlapped with Living Area — a reminder that more features don't always help if they're redundant

## Data Source
[House Prices - Advanced Regression Techniques (Kaggle)](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

*Note: raw data file not included in this repo — download `train.csv` directly from the Kaggle link above.*
