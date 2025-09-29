# Stock-Market-Forecasting-with-ARIMA-and-SARIMAX
## 📌 Project Overview
This project focuses on forecasting **Google (GOOGL) stock prices** using **time series models** such as **ARIMA** and **SARIMA**. The workflow includes data extraction, visualization, stationarity checks, decomposition, and hyperparameter tuning to select the best model for accurate predictions.

---

## 🛠️ Tools & Technologies
- **Python**
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Plotly, Statsmodels, pmdarima, yfinance, scikit-learn
- **Techniques:** Time Series Analysis, ARIMA, SARIMA, Seasonal Decomposition, Hyperparameter Tuning

---

## 🔑 Steps Implemented

1. **Data Collection**
   - Downloaded historical stock prices for **Google (GOOGL)** from Yahoo Finance using `yfinance`.
   - Defined the date range: last **365 days** from today.

2. **Data Preprocessing**
   - Cleaned and converted columns to numeric.
   - Selected the `Close` price for analysis.

3. **Exploratory Data Analysis (EDA)**
   - Visualized stock trends using **Plotly line charts**.
   - Decomposed the series into **Trend, Seasonality, and Noise**.
   - Performed **ADF test** for stationarity check.
   - Plotted **ACF & PACF** for lag correlation insights.

4. **Modeling**
   - Applied **ARIMA** and **SARIMA** models.
   - Conducted **auto_arima** for automated parameter selection.
   - Implemented **hyperparameter tuning** with grid search on SARIMA to minimize **AIC** score.

5. **Forecasting**
   - Forecasted the next **30 days** of Google stock prices.
   - Compared **Actual vs Predicted** values with visualizations.

---

## 📊 Visual Insights
- **Line plots** of historical prices.
- **Decomposition** of trend, seasonality, and residuals.
- **Autocorrelation & Partial Autocorrelation plots**.
- **Forecast plots** comparing actual and predicted prices.

---
