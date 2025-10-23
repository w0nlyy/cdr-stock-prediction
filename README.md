Short description:
This project implements a multi-model study for forecasting 5-day log returns of CD Projekt (CDR) using historical OHLCV data (2020–2024, source: investing.com). The goal is to compare classical and modern approaches (Linear Regression, XGBoost, LSTM, TFT, Random Walk baseline) and provide concise, reproducible results.

Key facts:
- Company: CD Projekt S.A. (CDR)  
- Data: Daily OHLCV, 2020–2024 (source: investing.com).  
- Target: 5-day log-return: 'y_t(5) = ln(P_{t+5} / P_t)'  
- Environment: Python (pandas, numpy, scikit-learn, xgboost, tensorflow/keras, pytorch/pytorch-lightning + pytorch-forecasting)

Models compared:
- Random Walk (baseline)  
- Linear Regression (OLS)  
- XGBoost (gradient-boosted trees)  
- LSTM (sequence model)  
- Temporal Fusion Transformer (TFT)

Evaluation metrics:
- RMSE, MAE, MAPE, R², Hit Rate (directional accuracy)

Usage:
1. Run the notebook sequentially; keep the code unchanged.  
2. Review evaluation cells for the final metric table and plots.  
3. Python version 3.10

