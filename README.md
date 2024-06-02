# Complete-TS-Forecasting-System
Complete Time Series Forecasting System for Different Industry Applications

## DataSets: 
1. Airline Passengers (Retrieved From Kaggle: https://www.kaggle.com/datasets/rakannimer/air-passengers)
2. Weather (Retreived From Kaggle: https://www.kaggle.com/datasets/vivekvivek13/weather-forecasting/data)
3. Stock Prices - Apple Stocks (Retrieved From Kaggle: https://www.kaggle.com/datasets/suyashlakhani/apple-stock-prices-20152020)
4. Electricty Price & Demand (The dataset includes a four-year record of weather data https://openweathermap.org/api electrical consumption, pricing, and generation data for Spain ENTOSE website)

## Airline Passengers 
In this project we are going to use airline-passengers dataset for time forecasting and we are also predicting Passengers for next 10 days

Time series analysis is a statistical method to analyse the past data within a given duration of time to forecast the future. It comprises of ordered sequence of data at equally spaced interval. To understand the time series data & the analysis let us consider an example. Consider an example of Airline Passenger data. It has the count of passenger over a period of time.

## Stock Price Prediction
Predicting the stock market has been the bane and goal of investors since its inception. Every day billions of dollars are traded on the stock exchange, and behind every dollar is an investor hoping to make a profit in one way or another.

Entire companies rise and fall daily depending on market behaviour. If an investor is able to accurately predict market movements, he offers a tantalizing promise of wealth and influence.

Let’s see how to predict stock prices using Machine Learning and the python programming language. I will start this task by importing all the necessary python libraries that we need for this task:

## Electricty Demand & Price - w/Weather
This is a time series forecasting problem where two distinct datasets of energy and weather data are used. The energy consumption and weather data from various cities in Spain are combined to create a multivariate time series forecasting problem. The energy dataset contains features related to the generation of energy from different sources like fossil fuels, wind, and coal. On the other hand, the weather dataset contains features related to various weather metrics such as temperature, humidity, pressure, wind speed, etc.

The dataset includes a four-year record of weather data https://openweathermap.org/api electrical consumption, pricing, and generation data for Spain ENTOSE website . The public ENTSOE portal was used to retrieve the consumption and generation data, while the Spanish TSO Red Electric España was used to obtain the settlement prices TSO website.

## Methdology
The code for each sub-project consists of 4 main parts:

1. Data loading and feature exploartion: This part uses os and pandas to load, process the data into a dataframe, plotting correlation matrix on both the dataset.
2. Preprocessing: Involves getting rid of Null values, selecting features required hour,weekday, month, year from the data and plotting visualization, followed by normalizing and reshaping the data follwed by using The Dickey-Fuller test to check if thr data us stationary
3. Model building and training: This part using PCA to select the features necessary,normalizing target variables and then building forecasting models With XGBoost, GRU, LSTM, CNN, CNN-LSTM,LSTM attention, GRU-XGboost, LSTM attention-XGboost.
We plot the train an validation Mean Absolute Error for each case and also compare the scores across the different models towards the end.

## Requirements
To run the code, you need to install the following libraries:

- matplotlib
- Numpy, panda, math
- Seaborn
- Xgboost
- Tensorflow
- keras
- Scikit Learn

## Models
Models used in this project :
1. Machine learning:
      - XGboost Regressor
3. Deep learning/Stacked models :
      - GRU
      - LSTM
      - CNN
      - CNN-LSTM
      - LSTM-Attention
5. Hybrid methods:
      - GRU-XGBoost
      - LSTM-Attention-XGBoost


## Results
<img width="366" alt="Screenshot 2024-06-02 at 5 45 28 PM" src="https://github.com/hbsedki/Complete-TS-Forecasting-System/assets/150509637/0afbf580-6169-42ba-b04a-c701f3fe9050">

