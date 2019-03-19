<<<<<<< HEAD
# Datalit_Midterm
**Amazon Stock price predicction using linear regression**

## To know more:
Datalit course by Siraj Raval and TheSchoolOfAI : https://www.theschool.ai/courses/data-lit

## Problem statement:
Write a Python script that uses linear regression to predict the price of a stock. Pick any company you’d like. This is a fun exercise to learn about data preprocessing, python, and using machine learning libraries like sci-kit learn. Submit your github repository

## Steps taken:
1. Since the data comes from the Qiandl API all of the data is preprocessed, so no need to check for NA values
1. Stored the data in a dataframe
1. In order to predict the price, we only needed the Date and Close variable, so we selected those 2 from the dataframe and stored it in variables
1. Converted them to a compatible vector (Compatible dimensional conversion)
1. Applied the data split using ```pytohn train_test_split ``` with a test size of 0.33
1. Initialized ```python LinearRegression()``` as lreg
1. Applied the fit function to the training data
1. Predected the YHat value using xtest
1. Plotted 2 plots of Actual Vs Predicted data for training and testing

**Here's the ouput for testing data**
![Prediction of testing plot](https://i.imgur.com/f9OM6Yk.jpg)

## Resources Used:
* https://programmingforfinance.com/2018/01/predicting-stock-prices-with-linear-regression/
* https://enlight.nyc/projects/stock-market-prediction/
=======

>>>>>>> 766e438351e7914a071b60be63bf89918b60243a
