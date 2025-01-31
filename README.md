# Time-Series-Forecasting-Bus-Ridership-Analysis

### Overview
This project applies time series forecasting techniques to analyze monthly bus ridership data. The goal is to evaluate stationarity, develop ARIMA models, and compare forecasting accuracy.

### Features
- Data Splitting: Train (up to Dec 2018) and Test (Jan – Jun 2019) using the xts package.
Exploratory Data Analysis (EDA): Time series plots, ACF analysis, and stationarity tests.
Baseline Model: Auto-ARIMA without seasonality to establish an initial model.
Model Evaluation: ADF test, differencing analysis, and residual autocorrelation checks.
Forecasting & Comparisons: Testing multiple ARIMA models and selecting the best based on RMSE and ACF1 of residuals.

### Dependencies
This project requires R packages for time series analysis and forecasting.

### Usage
Preprocess Data: Convert data to an xts object and split into training and test sets.
Perform EDA: Visualize trends, check stationarity, and analyze autocorrelation.
Train & Compare Models: Fit Auto-ARIMA and additional custom ARIMA models.
Evaluate Forecasts: Compare RMSE and residual autocorrelation to determine the best model.

### Results
The optimal ARIMA model was selected based on lowest test RMSE and train ACF1, confirming that differencing was necessary to make the series stationary.

📂 For full details, refer to the R Markdown file. 🚀
