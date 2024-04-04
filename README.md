# Stock Price Prediction Project

## Overview

This project aims to predict stock prices using machine learning models. It includes data preprocessing, feature engineering, model training, and evaluation steps. Three different types of models are explored: Lasso regression, XGBoost, and LSTM neural network.

## Table of Contents

1. [Overview](#overview)
2. [Table of Contents](#table-of-contents)
3. [Dataset](#dataset)
4. [Data Preprocessing](#data-preprocessing)
5. [Feature Engineering](#feature-engineering)
6. [Model Training](#model-training)
7. [Evaluation Metrics](#evaluation-metrics)
8. [Results](#results)
9. [Future Work](#future-work)
10. [License](#license)

## Dataset

The dataset used in this project consists of historical stock price data from the JPX Tokyo Stock Exchange. It includes features such as Open, Close, High, Low, Volume, and ExpectedDividend.


## Data Preprocessing

The raw stock price data is preprocessed to handle missing values, adjust for stock splits and dividends, and ensure data consistency.

## Feature Engineering

Various features are engineered from the raw stock price data, including return metrics, volatility measures, amplitude, RSI (Relative Strength Index), 52-week high, BIAS, and more.

## Model Training

Three different models are trained:
- Lasso regression
- XGBoost
- LSTM (Long Short-Term Memory) neural network

The models are trained using appropriate hyperparameters and evaluated on both training and testing datasets.

## Evaluation Metrics

The performance of each model is evaluated using the following metrics:
- R^2 (coefficient of determination)
- RMSE (Root Mean Squared Error)
- Sharpe ratio

## Results

The evaluation results indicate the performance of each model in predicting stock prices. The best-performing model is determined based on the chosen evaluation metric.

## Future Work

Potential future improvements to the project include:
- Experimenting with additional features
- Fine-tuning hyperparameters of the models
- Exploring ensemble methods for improved predictions

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
