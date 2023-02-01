# Project Name
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## Assignment Part-I

#### Business Understanding

- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

- The company wants to know the following things about the prospective properties:

   - `Which variables are significant in predicting the price of a house`, and

   - `How well those variables describe the price of a house`.

 

- Also, determine the `optimal value of lambda for ridge and lasso regression`.

#### Business Goal:

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

#### Business Risk:

- Predicting a higher sale price for a house would not attact the customers which would lead to a loss to the company
- Predicting a lower sale price for a house would lead to reduces profit margin for the company

#### Requirement:

- Which variable are significant in predicting the sale price of the house?
- How well those variabe describe the sale price of the house?
- Optimal value of lambda for ridge and lasso regression?

## General Information
- Steps for crreating a Regularized regression model :
<ol>
    <li>Read and Understand the data</li>
    <li>Data Exploration</li>
    <li>Feature Engineering</li>
    <li>Data Preprocessing</li>
    <li>Model Building, Tuning & Evaluation</li>
    <li>Comparing the two models</li>
    <li>Inferences for 'Housing Price Prediction'</li>
    <li>Coding for answering the subjective questions</li>
</ol>
- Data Set : train.csv

## Conclusions
<div class="alert alert-block alert-danger">
    <span style='font-family:Georgia'>
        <b>Optimal value of alpha  </b>
        <ol>
            <li>Optimal value of lambda for Ridge Regression = 10</li>
            <li>Optimal value of lambda for Lasso = 0.001</li>
        </ol>
        <b>The most important predictor variables are:</b>
        <ol>
            <li>GrLivArea</li>
            <li>OverallQual_8</li>
            <li>OverallQual_9</li>
            <li>Functional_Typ</li>
            <li>Neighborhood_Crawfor</li>
            <li>Exterior1st_BrkFace</li>
            <li>TotalBsmtSF</li>
            <li>CentralAir_Y</li>
        </ol>
        <b>A model is robust when any variation in the data does not affect its performance much.

## Technologies Used
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- sklearn
- statsmodel


## Acknowledgements
- https://www.geeksforgeeks.org/
- https://seaborn.pydata.org/
- https://plotly.com/
- https://pandas.pydata.org/
- https://learn.upgrad.com/


## Contact
Created by [@prachipokharkar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->