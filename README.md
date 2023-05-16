# **MLG-2-Assignment1-Group-6**
## -- Team Members -- 
* ### Danae Marais : 578326
* ### Vuyo Fortune Mathe : 578376
* ### Roan Palm : 578632
* ### Henko Meyer : 578420

## Abstract
The selling prices of residential properties in Ames, Iowa, may be predicted with accuracy using a regression model that can handle complicated datasets with a high number of characteristics, missing values, and non-linear correlations between the features and target variable. The aim is to forecast the sale price of each property based on the dataset's many properties, which include the size of the house, location, age, and quality, among others. Based on the root mean squared error (RMSE) metric, a model is created that can forecast home selling prices with a minimum amount of error. It is necessary to have understanding of sophisticated regression techniques, data analysis approaches, feature engineering, and model selection abilities.


## Introduction
Predicting housing prices is a crucial goal. Recent research has shown that asset prices can aid in forecasting inflation and production. Housing price fluctuations can reveal information about consumption and inflation. The housing market is crucial to the business cycle. Understanding supply and demand requires research on housing sales and pricing.

Models that can predict home prices can give decision-makers and economists insight into the future state of the economy, assisting them in creating better policies. Estimating prepayments, housing mortgages, and housing affordability can also be helpful to economists. Machine learning has gained popularity recently as a method for forecasting property values based on their characteristics. House price forecasting is frequently handled as a regression issue.

## Dataset
Under "House Prices: Advanced Regression Techniques" on Kaggle, the housing dataset is accessible. The training data are in the "train.csv" file, whereas the testing data are in the "test.csv" file. The training data consists of 80 columns that correspond to the features of those homes and 1460 rows that represent the data from 1460 houses. The testing data also includes information on 1461 dwellings and their 79 features. We, however used the training set as our main dataset and divided that into a train set and test set.

## Feature Engineering
* All of the tests were run in a Jupyter notebook with a Python kernel.  Data loading, processing, and transformation were performed using the Pandas and NumPy libraries. To plot visuals, Matplotlib was utilised.
* Pre-processing the data was crucial due to the big dataset. For example, since it is not necessary for prediction, the Id column was first removed from the features. 


## Data Modelling
* Random Forest Regressor: 0.8855230238634435

Between the actual values and the forecasted values, scatter plots were also seen. Overall, it was found that the model had a significant accuracy to predict the values.

