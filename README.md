# Air Passenger Prediction using ARIMA

![Python](https://img.shields.io/badge/python-3.7%2B-blue)
[![Kaggle](https://img.shields.io/badge/notebook-Kaggle-blue)]([link-to-kaggle-notebook](https://www.kaggle.com/code/siddp6/air-passengers-monthly-prediction-using-arima/notebook?scriptVersionId=140384856))

Predicting the number of air passengers in upcoming months using the ARIMA (AutoRegressive Integrated Moving Average) model. This project utilizes the [Air Passenger Dataset](https://www.kaggle.com/datasets/rakannimer/air-passengers) from Kaggle to demonstrate the application of the ARIMA model for time series prediction.

## Table of Contents

- [Introduction](#introduction)
- [ARIMA Model](#arima-model)
- [Usage](#usage)
- [Contributing](#contributing)
- [Results](#results)
- [Resources](#resources)

## Introduction

This project aims to provide an illustrative example of using the ARIMA model to forecast the number of air passengers in the upcoming months. The dataset contains historical passenger data, which is used to train the model and make predictions. The steps to determine the optimal ARIMA parameters (p, d, q) are explained, along with the process of testing for stationarity using the Augmented Dickey-Fuller (ADF) test.

## ARIMA Model

ARIMA (AutoRegressive Integrated Moving Average) is a popular time series forecasting method that combines autoregressive (AR) and moving average (MA) components with differencing to make the data stationary. In this project, we demonstrate the process of selecting the appropriate values for the ARIMA parameters:
- **p (AR order)**: Determined using the Partial Autocorrelation Function (PACF).
- **d (Integration order)**: Determined by checking the stationarity of the time series using the Augmented Dickey-Fuller (ADF) test.
- **q (MA order)**: Determined using the Autocorrelation Function (ACF).


## Usage

1. Open the [Kaggle notebook](https://www.kaggle.com/code/siddp6/air-passengers-monthly-prediction-using-arima/notebook?scriptVersionId=140384856) to access the step-by-step demonstration of the ARIMA model for air passenger prediction.

2. Follow along with the notebook to understand how to preprocess the data, determine the ARIMA parameters, and make predictions.

3. Experiment with different parameter values and explore the performance of the ARIMA model.

## Results
![image](https://github.com/sidd6p/Air-Passengers-Prediction-ARIMA/assets/91800813/2055cd45-b062-451a-8f53-2439a4cce72c)
![image](https://github.com/sidd6p/Air-Passengers-Prediction-ARIMA/assets/91800813/1f5f6e6b-46ce-4f13-abbc-707cf748e786)


## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request. For major changes, please discuss your ideas in an issue before implementing them.

## Resources

- [Kaggle Discussion](https://www.kaggle.com/discussions/general/432826)
- [A Comprehensive Guide to ARIMA](https://www.machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/)


**Disclaimer:** This project is for educational purposes and serves as a demonstration of the ARIMA model for time series prediction. It is not intended for production use.


