# Project : Stock Prediction With Using Machine Learning Algorithms


### Table of Contents
•	[Motivation](#Motivation)

•	[Descriptions](#Description)

•	[Installation](#Installation)

•	[Data](#Data)

•	[Licensing, Authors, and Acknowledgements](#Licensing)


## Motivation <a name="Motivation"></a>

This project is capstone of Udacity Data Science Nanodegree. The goal of the project is to predict stock prices using machine learning algorithms . 



## Descriptions <a name="Descriptions"></a>

The project shows how the stock price is predicted by using Machine Learning Models . The project follows the steps below:

1. Load historical stock price data from Yahoo Finance.

2. Check for missing values and data cleaning.
 
3. Process Exploratory Data Analysis.

4. Perform data preparation and feature engineering for machine learning.

5. Train the regression models.

6. Validate the models.

7. Select the best model and make a recommendation.


I use various machine learning models to see if they would preciously predict the stock price. These are the machine learning algorithms that I use in the project. Decision Tree Regressor, Support Vector Regressor(SVR), LassoCV, RidgeCV, Stochastic Gradient Descent(SGD).
The best model will recommend the best stock price prediction for the investors.

## Installation <a name="Installation"></a>

• pandas

• numpy

• matplotlib

• sklearn

• seaborn


## Data <a name="Data"></a>

Stock market historical data can be found from many places, but I choose to download from https://finance.yahoo.com/.  
I select Adobe stock for this project and pull up the historical data from yahoo finance. It is easy to fetch all financial data from yahoo with yfinance module.
I import the yfinance module with import yfinance as yf method. The data covers  from 01-01-2010 to 06-17-2021.

## Licensing, Authors, and Acknowledgements<a name="Licensing"></a>

Thank to  Udacity for a great project, and Yahoo.com for the dataset.

