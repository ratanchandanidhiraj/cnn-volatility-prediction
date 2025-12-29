# Market Volatility Prediction using CNN
Stock market volatility prediction using CNN and historical price data


## Overview
This project implements a Convolutional Neural Network (CNN) model to predict stock market volatility using historical price data. The data is fetched dynamically using the yFinance API, making the analysis fully reproducible without relying on static datasets.

## Objective
- Model and predict market volatility from historical stock prices
- Apply deep learning techniques to financial time-series data
- Evaluate model performance using regression metrics

## Data Source
- Historical stock price data fetched using `yfinance`
- Example ticker: AAPL
- Time period: 2015–2025

## Methodology
- Download adjusted close prices using yFinance
- Generate volatility features from price movements
- Prepare rolling time-series windows
- Train a 1D CNN model for regression
- Evaluate using RMSE and MAE

## Tools & Libraries
- Python
- NumPy
- Pandas
- TensorFlow / Keras
- yFinance
- Scikit-learn

## Model Evaluation
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)


