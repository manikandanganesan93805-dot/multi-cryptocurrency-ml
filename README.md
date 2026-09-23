# Multi-Coin Cryptocurrency Price Movement Prediction Using Machine Learning

## Project Overview

This project predicts the next-day price movement of multiple cryptocurrencies as **UP (1)** or **DOWN (0)** using a Random Forest machine learning model.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Random Forest
* Gradio
* Google Colab
## Cryptocurrencies

* BTC-USD
* ETH-USD
* BNB-USD
* SOL-USD
* XRP-USD
* ADA-USD
* DOGE-USD
* AVAX-USD

## Features

* Open
* High
* Low
* Close
* Volume
* 1-Day Return
* 7-Day Moving Average
* 14-Day Moving Average
* 7-Day Volatility

## Machine Learning Model

**Random Forest Classifier**

The model predicts:

* `1` → UP
* `0` → DOWN

## Project Workflow

1. Load cryptocurrency dataset
2. Clean and preprocess the data
3. Sort data chronologically
4. Perform feature engineering
5. Create the target variable
6. Split data into training and testing sets
7. Train the Random Forest model
8. Evaluate model performance
9. Predict cryptocurrency price movement
10. Display predictions using Gradio

## Application

A Gradio interface allows the user to select a cryptocurrency and receive:

* Predicted movement
* UP probability
* DOWN probability
* Random Forest model
* Test accuracy
