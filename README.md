# Predicting House Prices in King County, USA using Machine Learning and Deep Learning

## Overview
The project aims to predict prices based on data (square feet living, number of rooms, building age etc.) on houses in King County. Predictions were made using regression models and tensorflow. 

## Implementation details
* As a result of the models trained in our project, it was aimed to have r2_score above 0.8 and mean squared error below 100000. 
* Explororaty data analysis, data visualizaton and feature engineering have been done to achieve the goal.
* Firstly, exploratory data analysis was performed. Examined how data affects house prices. Outliers were determined by visualizing the data. Outliers were removed by feature engineering. Data that would adversely affect the prediction were removed. Important data were identified. With dummy variable, string type data is converted to int type for the model to detect.
* 20 percent of the data was reserved for testing. Training was conducted using 7 different machine learning models. r2 score, MSE and MAE results of each model are listed as a table. The intended r2 score and MSE in 5 models were obtained. The most efficient estimation was obtained in the XGradientBoosting model.
* House Prices prediction was also done using tensorflow. Relu used as activation fanction. Adam used as optimizer. epochs 1500, batch size set to 120.
* With deep learning, the targeted r2 score and MSE were achieved.
