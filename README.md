# Project Name
> Prediction of housing prices based on multiple predictor variables through regularized regression.


## Table of Contents
* General Info
	Steps followed as 
	EDA, test-train split
	Scaling 
	Model Fit & Prediction with linear regression along with Ridge & Lasso regularization 
	Residual check, Prediction on test with R2 score
	Best method by comparing all above aspects
* Tools use:
	Python jyupitar notebook
	scikit-learn & statsmodel liabraries for regression fitting
      Ridge & Lasso liabraries as regularization techniques
* Conculsions:
	Finalized Ridge regression model with R2 score on train data 94.7% & on 89.4% test data.

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Conclusions
1. Linear regression without any regularization gave unrealistic results on test R2 score
2. Lasso model fitting gave better results on training data than Ridge model.
3. Ridge model finalized, as it performed well on test(unseen data) compared to Lasso 
Top 10 predictor variables are plotted with Ridge & Lasso. Except 2, 3 variables other variables are different for both methods.


## Technologies Used
- library - scikit-learn & statsmodel (Regression model fitting, Ridge & Lasso model fitting, Grid Search CV)

## Acknowledgements
Give credit here.
- This project was inspired by UpGrad

## Contact
Created by [@ksoham9552] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->