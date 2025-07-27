# 📈 Cryptocurrency Price Forecasting Project

This project is a complete end-to-end pipeline for **scraping**, **cleaning**, **analyzing**, and **predicting** cryptocurrency prices using historical data from [CoinMarketCap](https://coinmarketcap.com/). It supports advanced modeling using multiple machine learning algorithms including ARIMA, Random Forest, SVR, Gradient Boosting, and XGBoost.

---

## 🧠 Project Overview

The goal of this project is to build a robust system for:

- Scraping historical cryptocurrency data (from 2014 to today)
- Cleaning and imputing missing data using advanced techniques (e.g., KNNImputer)
- Conducting data analysis and visualization
- Modeling cryptocurrency prices using time series and machine learning models
- Forecasting future prices for any selected cryptocurrency (e.g., BTC, ETH)
- Visualizing forecasted trends for the next 60 days

---

## 🔧 Features

✅ Automatic historical data scraping from CoinMarketCap  
✅ Data cleaning with robust error handling  
✅ Missing value imputation using KNN + cross-validation  
✅ Time series feature generation  
✅ Model training and evaluation with R², MSE, and RMSE  
✅ Multi-model support: `ARIMA`, `RandomForest`, `SVR`, `GradientBoosting`, `XGBoost`  
✅ Dynamic prediction and visualization for any crypto symbol  
✅ Detailed comparative and correlation analysis  

---

## 📊 Machine Learning Models Used

- **ARIMA** for classic time series modeling  
- **Random Forest Regressor**  
- **Support Vector Regressor (SVR)**  
- **Gradient Boosting Regressor**  
- **XGBoost Regressor**

Model performance is evaluated using:
- R² Score
- MSE and RMSE

---
## 🚀 Getting Started

### Requirements

Install required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn keras xgboost statsmodels beautifulsoup4 requests
