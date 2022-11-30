# Regression and predictive modeling of time series sales data

Rossmann is one of the largest drugstore chains in Europe with over 3,000 drug stores in 7 European countries. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. Accurate sales projection depends largely on store's unique circumstances and the timing of the prediction. 

In this notebook, I built machine leaning and neural network models to regress historical sales data and predict daily sales for 1115 Rossmann stores in Germany. The dataset used in this work can be found on Kaggle website.

https://www.kaggle.com/competitions/rossmann-store-sales/data

The structure of this Jupyter Notebook is as follows:

1. Prepare Problem
a) Load libraries
b) Load dataset

2. Summarize Data
a) Descriptive statistics
b) Data visualizations

3. Prepare Data
a) Data Cleaning
b) Data Transforms

4. Evaluate Algorithms
a) Split-out validation dataset
b) Spot check and compare algorithms 
   Machine learning: Linear Regression, Random Forest, and XGBoost
   Deep learning: Keras Sequential neural network

5. Finalize Model
a) Predictions on validation dataset
b) Save the model for later use


