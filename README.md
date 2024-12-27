# [Deep Learning for Financial Time Series Forecast Fusion and Optimal Portfolio Rebalancing](https://ieeexplore.ieee.org/document/9626945)

This repository contains code and resources for leveraging deep learning techniques to forecast financial time series and optimize portfolio rebalancing. It includes forecasting models, prediction outputs, and portfolio management tools.

## Repository Structure

### 1. Forecasting Models

- Organization: Each stock has its own folder.
- Contents:
  - Hyperparameter Optimization: Jupyter Notebooks for optimizing LSTM and GRU hyperparameters.
  - Forecasting Code: Implements the forecasting models.

### 2. Predictions

- CSV Files: Stores predictions from each forecasting model.
  - Format: Predictions for day 𝑡 + 5 t+5 are saved at day 𝑡 t.
- Pre-Processing:
  - `Pre_processing_predictions.ipynb`: Aggregates model predictions into new CSV files containing vectors of expected returns for each model.

### 3. Portfolio Management

- Generated Files: Results produced by `Pre_processing_predictions.ipynb`.
- Portfolio Management Code:
  - `Portfolio_Management.ipynb`: Implements portfolio rebalancing strategies.
- Risk-Free Rate Calculation:
  - `Calculating RFR.ipynb`: Computes the risk-free rate.

### 4. Stocks

- Dataset: Contains the historical stock data used for model training and evaluation.
