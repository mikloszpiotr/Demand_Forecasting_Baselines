# Demand Forecasting Baselines

This repository contains a hands-on Jupyter notebook that builds and evaluates **baseline** demand forecasting models on a single time series. [file:1]

The goal is to provide a clean, reproducible benchmark for comparing simple statistical methods and basic machine learning approaches before moving to more complex architectures. [file:1]

---

## Project Overview

The notebook walks through the full workflow: from loading and preparing time series data, through feature engineering, to training and evaluating several forecasting models using common error metrics. [file:1]

It is designed as a practical starting point for supply chain and analytics practitioners who want quick, explainable baselines for daily or weekly demand. [file:1]

---

## Implemented Models

The following models are implemented and evaluated side by side: [file:1]

- **Naive** (last observation carried forward). [file:1]  
- **Moving Average** (7‑day window). [file:1]  
- **ARIMA** (univariate time series). [file:1]  
- **Linear Regression** with time and calendar features. [file:1]  
- **Random Forest Regressor** with lag and calendar features. [file:1]  
- **XGBoost Regressor** with lag and calendar features. [file:1]  

Each model is evaluated using MAE, RMSE, MAPE, \(R^2\), and simple train/prediction time measurements. [file:1]

---

## Repository Structure

```text
.
├── Demand_Forecasting_Baselines.ipynb  # Main notebook with full workflow
└── README.md                           # Project description and usage
