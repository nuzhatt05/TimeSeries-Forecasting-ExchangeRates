# Forecasting Exchange Rates using Time Series Analysis

This repository is focused on forecasting **exchange rates** using **ARIMA** and **Exponential Smoothing** models on the `exchange_rate.csv` dataset.  
The assignment demonstrates time series exploration, preprocessing, model fitting, diagnostics, forecasting, and model comparison.

---

## Objective
To apply **ARIMA** and **Exponential Smoothing** methods for predicting future exchange rates.  
This assignment provides practical exposure to **time series forecasting techniques**, parameter selection, and evaluation.

---

## Files Included

| File Name                  | Description |
| -------------------------- | ------------------------------------------------------------ |
| TimeSeries_Forecasting.ipynb | Jupyter Notebook containing preprocessing, ARIMA & Exponential Smoothing models, evaluation, and visualization |
| Timeseries.docx            | Word document containing the problem statement and assignment details |
| exchange_rate.csv          | Dataset containing historical exchange rates (date and USD to AUD) |

---

## Dataset Description

The **exchange_rate dataset** contains historical values of USD to Australian Dollar.  

- **date** – Date of observation  
- **Ex_rate** – Exchange rate (USD to AUD)  

---

## Tools & Libraries
* Jupyter Notebook  
* Python 3.x  
* Libraries:  
  - `pandas`  
  - `matplotlib`, `seaborn`  
  - `statsmodels` (ARIMA, Exponential Smoothing)  
  - `scikit-learn` (error metrics)  

---

## Tasks Performed
* **Data Exploration:** loaded and visualized time series, analyzed trends, seasonality, anomalies  
* **Preprocessing:** handled missing values and prepared dataset for modeling  
* **ARIMA Model:** parameter selection via ACF & PACF plots, fitted ARIMA model, residual diagnostics, and forecasting  
* **Exponential Smoothing:** applied Simple, Holt’s, or Holt-Winters models depending on trend/seasonality, tuned parameters, and forecasted values  
* **Evaluation & Comparison:** evaluated forecasts using MAE, RMSE, and MAPE; compared ARIMA vs Exponential Smoothing performance  
* **Conclusion:** summarized findings, discussed best-performing model, and practical insights for exchange rate forecasting  

---

## Status
Completed – dataset prepared, ARIMA and Exponential Smoothing applied, forecasts generated, error metrics computed, and models compared.  
This assignment provides hands-on experience in **real-world financial time series forecasting**.  

---

## Author
**Nuzhat** – Data Science Learner  
GitHub: [nuzhatt05](https://github.com/nuzhatt05)
