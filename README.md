# LSTM_StockPred
Predicting Stock Prices using LSTM in Python

This project demonstrates how to use a Long Short-Term Memory (LSTM) model to predict stock prices using Python.

## Getting Started
To run this code, you'll need to install the following packages:

`pandas`

`numpy`

`matplotlib`

`tensorflow`

`alpha_vantage`

`sklearn`

You'll also need to sign up for an API key from Alpha Vantage in order to retrieve stock data.

## Usage
The code retrieves intraday stock data for Google and trains an LSTM model to predict the closing price of the stock. The LSTM model is saved as a .h5 file, and can be used to make predictions on new data. The predicted stock prices are plotted against the actual stock prices to visualize the accuracy of the model.

To run the code, simply execute the `RealTimePred.ipynb` script.

## Acknowledgements
This project was created with the help of the Alpha Vantage API and the Keras library.
