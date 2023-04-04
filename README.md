# 
In this project 
I used Black Friday dataset for prediction Purchase as regression problem.
Firstly I deal with cleaning data set from missing value and some necassary transformation  and then made explonatory data analysis to understand data.
Following this to find which regression model give lowest RMSE score, I made pipeline for the purpose of encoding categorical variables and scaling numerical ones at the same time and adding model training into it.
After find best model which is XGBoost I tune it with OPTUNA instead of Grid Search CV. Because it is faster and supply different visualization graphs.
Besides I used Shapley as finding feature importance. It gave very comprehensive and upgraded result and graphs.
