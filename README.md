# ARIMA & SARIMA Time Series Models for Weather Prediction

### Overview
**Statistical time series modeling** to forecast weather data using Autoregressive Integrated Moving Average **(ARIMA)** and Seasonal ARIMA **(SARIMA)** models. The main aim of this project is to build a comprehensive pipeline to perform weather forecasting for the period January-March 2017.

### Dataset Features
The dataset provides training data on weather from 2013 to 2016 with an additional testing set for Q1 2017, which corresponds to the forecast interval. There are 4 parameters describing weather, that are meantemp, humidity, wind_speed, and meanpressure.

## Project steps
1. **Data Preprocessing:** Loading, converting and cleaning of the data.
2. **Exploratory Data Analysis (EDA):**
   - Exploring the dataset with descriptive statistics and frequency analysis.
   - Visualizing seasonal patterns and trend components
3. **Time Series Modeling:** 
   - Identifying data stationarity using ADF tests.
   - Differencing and decomposition to model trend and seasonality.
   - Building and tuning **ARIMA** and **SARIMA** models using AIC/BIC and grid search.
4. **Forecasting & Evaluation:**
   - Generate out-of-sample forecasts for 2017.
   - Comparing predictions with actual values using **MAE** and **RMSE**.
   - Visualizing forecast performance.


## Key Takeaways
- **ARIMA (AutoRegressive Integrated Moving Average):** Captures trend and autocorrelation in univariate time series.
- **SARIMA (Seasonal ARIMA):** models provided more accurate forecasts due to seasonal adjustment.
- **Model Selection:** AIC/BIC scores used to compare candidate models.
- **Residual Analysis:** Ensures models meet white noise assumptions.