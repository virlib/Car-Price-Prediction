# Car-Price-Prediction

In this project, I take a dataset with car features and price, and try to develop a model to predict the price. The maximum R score reached is <b> `0.8` </b> 

<b>1. Data Wrangling  </b>
  <li> Remove Null Values by replacing them with mean, mode or dropping those rows entirely based on the situation
  <li> Change datatypes of columns to better suit their values
  <li> Normalize Values such as length, width, height
  <li> Bin columns
  <li> Creating dummy variables
  
<b>2. EDA </b>
  <li> Explore and understand dataset
  <li> Find correlation among variables
  <li> Creating boxplots to understand dependence on categorical variables
  <li> ANOVA test to find out spread of variance
  
<b>3. Model Development </b>
  <li> Splitting data into train and test 
  <li> Fitting data into Linear Regression, Multiple Regression and Polynomial Regression
  <li> Finding out the best model based on R score and MSE
  
<b>4. Model Refining </b>
  <li> Working with folds
  <li> Finding out best parameter using Cross Validation and Grid Search CV
  <li> Creating Pipelines
