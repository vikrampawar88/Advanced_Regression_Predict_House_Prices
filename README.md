# Linear Regression to understand factors affecting demand of Bike Sharing
> In this project we are focused on building the advanced regression model using regularisation to understand the variables which are significant in predicting the price of a house & how well those variables describe the price of a house which will then be used by the management to manipulate strategy as per price variation with variables.


## Table of Contents
* [Problem Statement](#problem-statement)
* [Business Objective](#business-objective)
* [Solution Approach](#analysis-approach)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Team](#team)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

1. Which variables are significant in predicting the price of a house, and
2. How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

## Business Objective
Required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Solution Approach
1. Reading, Understanding & Cleaning the Data
2. Visualising the Data
3. Data Preparation for modelling
4. Splitting the Data into Training and Testing Sets
5. Model Building and Evaluation
6. Ridge Regression
7. Lasso Regression
8. Model Comparison
9. Conclusion

## Conclusions

Surprise Housing can keep track of below predictors affecting the price of the house.

<br/>

__Positive Coefficient Variables - suggest a high sale value__
<br/>

__GrLivArea :__ Above grade (ground) living area square feet
__OverallQual :__ Rates the overall material and finish of the house
__GarageCars :__ Size of garage in car capacity
__YearRemodAdd :__ Remodel date (same as construction date if no remodeling or additions)
__MSZoning :__ Identifies the general zoning classification of the sale
<br/>
<br/>

__Negative Coefficient Variables - suggest a decrease in sale value__
<br/>

__FireplaceQu :__ Fireplace quality
__ExterQual :__ Evaluates the quality of the material on the exterior
<br/>

## Technologies Used
- Python - Version 3.9.13
- numpy - Version 1.21.5
- pandas - Version 1.4.4
- matplotlib - Version 3.5.2
- seaborn - Version 0.11.2
- statsmodels - Version 0.13.2
- scikit-learn - Version 1.0.2
- sklearn - version 0.24.2
- Jupyter Notebook - Version 6.4.12
- Anaconda - Version 2.3.2

## Acknowledgements

## Team
[Vikram Pawar](https://www.linkedin.com/in/vikrampawar88/)


## Contact
Created by [@vikrampawar88] - feel free to contact me!



<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
