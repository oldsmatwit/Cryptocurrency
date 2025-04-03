# Cryptocurrency Price Prediction and Analysis
## Overview
This project explores the behavior of cryptocurrency markets, focusing on Bitcoin as a representative case study. The goal is to analyze historical price trends, identify the most volatile cryptocurrencies, investigate correlations between different cryptocurrencies, and predict future price movements using machine learning techniques. The primary machine learning model used for time series forecasting is the Long Short-Term Memory (LSTM) network, which allows for predicting cryptocurrency prices based on historical data and technical indicators.

## Project Objectives
### Historical Trend Analysis: 
Visualizing and understanding the price movement of Bitcoin and other cryptocurrencies over time.

### Volatility Measurement: 
Identifying the most volatile cryptocurrencies by calculating the standard deviation of their daily returns.

### Cryptocurrency Correlations: 
Analyzing how different cryptocurrencies correlate with each other in terms of price movements.

### Price Prediction: 
Using a machine learning model (LSTM) to predict the future prices of Bitcoin based on historical data and technical indicators.

## Datasets
This project uses several datasets available on Kaggle:

### Price History Dataset:

Contains historical price movements of various cryptocurrencies. Bitcoin was selected for this project due to its popularity and dominance in the market.

### All Cryptocurrencies Dataset:

Includes information on a wide range of cryptocurrencies, such as market cap, volume, and other attributes. Data was filtered to focus on relevant and high-volume cryptocurrencies.

### Cryptocurrency Pairs Dataset:

Provides minute-resolution data on cryptocurrency trading pairs. Data from this dataset was narrowed down to focus on Bitcoin pairs for simplicity and clarity.

## Data Preprocessing
Data cleaning was done using Excel, removing low-volume cryptocurrencies from the All Cryptocurrencies Dataset.

The Cryptocurrency Pairs Dataset was filtered to include only Bitcoin pairs, due to its familiarity and prominence in the market.

## Methodology
The analysis focuses on four key research questions:

### Historical Trends of Cryptocurrency Prices:

Line charts and moving averages were used to visualize price movements and identify trends in Bitcoin prices.

### Cryptocurrency Volatility:

Volatility was measured using the standard deviation of daily returns. A bar chart was created to show the top 10 most volatile cryptocurrencies.

### Correlation Between Cryptocurrencies:

Correlation matrices were used to analyze the relationships between the price movements of different cryptocurrencies.

### Price Prediction Using LSTM:

A Long Short-Term Memory (LSTM) network was implemented for time series forecasting. The LSTM model was trained on historical price data to predict future Bitcoin prices. The model uses features such as historical price movements and technical indicators for prediction.

## Installation
To run this project, you will need the following dependencies:

#### Python 3.x

#### numpy

#### pandas

#### matplotlib

#### scikit-learn

#### tensorflow

#### keras

#### bokeh

#### seaborn

## Usage
### Data Preparation:

Load the priceHistory dataset, which contains the historical Bitcoin closing prices.


### LSTM Model Training:

The LSTM model is created using the Keras Sequential API, with two LSTM layers and dropout for regularization.

Train the model using the training set and evaluate it on the test set.

### Prediction:

The trained model is used to predict future Bitcoin prices based on the last known data point from the test set. Predictions are made for the next 100 days.

### Visualization:

The results are visualized using matplotlib, seaborn, and bokeh, showing the historical Bitcoin prices, predicted prices for the test set, and future price predictions.

## Results
### Historical Price Analysis: 
Provides insights into the past price trends of Bitcoin.

### Volatility Analysis: 
Identifies the most volatile cryptocurrencies.

### Correlation Analysis: 
Shows how different cryptocurrencies move in relation to one another.

### Price Prediction: 
Uses the LSTM model to predict future Bitcoin prices, providing a basis for potential market forecasting.

## Conclusion
This project demonstrates the power of machine learning models, particularly LSTM networks, in predicting cryptocurrency prices. By leveraging historical data and technical indicators, it is possible to forecast future price movements in a highly volatile market like cryptocurrencies. This analysis provides valuable insights into the factors driving cryptocurrency price fluctuations and highlights the potential for predictive modeling in this field.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
