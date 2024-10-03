# Used Car Price Prediction

## Dataset
The data has various information about a car's specifications such as the make and model of the car, odometer reading, year of manufacture etc. that'll help decide the current value of a car. There are more features about each vehicle in the dataset which might not be relevant in this scenario that will be dropped accordingly. But to decide the vehicle's valuation after the deprecation from they're bought the dataset provides sufficient knowledge.

## One Problem One Solution
Buying and selling cars happens all around the year in the United States. The real challenge is when the owner doesn’t know what a car's valuation should be when he is selling or buying one. To address this problem, we intend to build a model that will take in specifications of the car and estimates its current market value. We used data that is scraped from automobile reselling website which consists of 426k records, and the dataset has 25 attributes. Nearly half the attributes might not be relevant in price prediction and that leads to feature selection. The data is analyzed and based on the results; a suitable model is applied for the prediction.

## Intuition
After analyzing the data, we inferred that the important attributes have many unique values. If the dataset has numerous unique sets of values for each record, it becomes very tough for the model to train and understand the trends. Therefore, a lot of data cleaning and preparation has been performed on the dataset, so it can be a better fit for the models.

## Goal
The goal of this project is to primarily solve the problem of predicting a used car's price. Also, this approach can be handy in predicting values where many attributes have influence over the result. If the target value is spread over a very big range of values, this model will be an approach or a motivation for future developments.

## Pre-requisites 
To run this project, we need the following a python environment and the following libraries that are imported and utilized in the project.
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - plotly
  - sklearn
  - xgboost




