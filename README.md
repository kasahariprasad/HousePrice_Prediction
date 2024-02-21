House Price Prediction - Advanced regression Assignment
------------------------------------------------------------------------------------------------------

The solution is divided into the following sections:

    Data understanding and exploration
    Data cleaning
    Data preparation
    Model building and evaluation
    Observation and inference

Skewness: 1.882876
To correct/reduce Skewness we apply log 
We select features that contribute to Saleprice which is target variable
Try Lasso and Ridge regression to this to get details of what are features contributing to Final Sale Price
It is proven that Lasso regression is best fit for this model
Final inference:

#### The higher values of positive coeeficients suggest a high sale value.

#### Some of those features are:-
 |  Feature  |  Description  |
 |  ---  |  ---  |
 |  GrLivArea  |  Above grade (ground) living area square feet  |
 |  OverallQual  |  Rates the overall material and finish of the house  |
 |  OverallCond  |  Rates the overall condition of the house  |
 |  TotalBsmtSF  |  Total square feet of basement area  |
 |  GarageArea   |Size of garage in square feet  |
        
#### The higher values of negative coeeficients suggest a decrease in sale value.

#### Some of those features are:-
          PropAge  
          MSSubClass
