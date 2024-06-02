# Project Overview

Project Team:
- Selena Passeno
- Cole O'Neill
- Justin Clawson
- Joel Fisher
- Zac Williams

Using real estate data gathered from a public dataset on Kaggle, our group is trying to solve a major dilemma for the average home-buyer in Michigan. 

**What will the features for upcoming houses for sale in Michigan look like?**

In order to solve this dilemma, our team will create several machine learning models trained on the Kaggle dataset and use Root Mean Squared Error as our metric for determining the best model. thi will allow us to find the best model to use for predicting future home sale prices in Michigan based on the data we gathered.  

# Data Cleaning and Preparation

Starting with over 2 million records, 12 columns, and 45 states in the U.S, we focused our attention on houses that have been sold in Michigan. Additionally, we transformed our data further by limiting the sale prices of houses in Michigan between $50,000 and $1,000,000 as well as removing columns that we believed to be unnecessary for our models. 

After preforming data cleaning, we were left with approximately 4300 records and 3 features (# of beds, # of baths, house size) to train our models on. 

# Models Used

- Linear Regression
- TWO Neural Networks.
- and compared the Root Mean Squared Error 

# Results of Our Project

The results of our models showed that our FIRST Neural Network had the lowest Root Mean Squared Error which we consider to be the model that fits best with our home sales data. From our data gathering and cleaning along with our model fitting, training and testing, we are able to use our Neural Network to predict the cost of future prices for houses in Michigan.

Multiple Linear RMSE = 119,239
Random Forest RMSE = 282,347
Decision Trees RMSE = 286,488
Joel Neural Network RMSE = 111,012
Justin’s Neural Network RMSE = 116,000

# Github Repository Documentation

- **michigan_homes.csv** : Project datasource gathered from Kaggle.
- **Group2_Project4 v4 outline.pptx** : Project Powerpoint.
- **LinearRegression (2).ipynb** : Notebook containing our Linear Regression machine learning model.
- **Project_4_Neural_Network.ipynb** : Notebook containing our FIRST Neural Network machine learning model.
- 





