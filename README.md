# Predicting Housing Price
> A US-based housing company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
The company is looking at prospective properties to buy to enter the market. We are required to build a regression model using regularisation in order to predict the actual value of the properties and decide whether to invest in them or not. We need to find significant variables in predicting the price of a house.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

# Overview
- This assignment is a programming assignment wherein we have to build a regression model using regularisation with Ridge and Lasso methods to predict the actual price of the property.

- find significant variables in predicting the price of a house  
- how well thee variables describe the price of a house?
- determine the optimal value of lambda for ridge and lasso regression.
- data set has been given in problem "train.csv"

# Background
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
# Dataset
Data set has been given in problem "train.csv", where SalePrice is the target variable.

## Conclusions
- The target variable is cnt, which is a numerical value hence have followed regression model. As this is multicollinear we are using Lasso and ridge regression.
- The optimal lambda value in case of Ridge and Lasso is as below:
  Ridge - 5.0 Lasso - 0.0007 The Mean Squared error in case of Ridge and Lasso are:
  Ridge - 0.11795124311878702 Lasso - 0.11833529463591849 The Mean Squared Error of Lasso is slightly higher than that of Ridge
 Hence based on Lasso, the feature that affect the price are

Exterior1st_BrkComm, GrLivArea, MSSubClass_160,MSZoning_FV, YearBuilt,Neighborhood_Crawfor, GarageType_No Garage,OverallQual,TotalBsmtSF, Neighborhood_StoneBr

## Technologies Used
Python 3 is used with below libraries:
 pandas numpy pandas numpy matplotlib.pyplot, seaborn, statsmodels,sklearn,and (LinearRegression, r2_score,MinMaxScaler from sklearn,GridSearchCV, from sklearn.linear_model Lasso, Ridge)


## Acknowledgements
Give credit here.
- This project was inspired by Upgrad team Module 'Advanced Regression'
- Reference: https://learn.upgrad.com/course/5883/segment/35178/207528/636292/3227295.


## Contact
Created by @jays-26 !

