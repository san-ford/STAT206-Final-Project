

# Predicting Sale Price of Houses in Ames, IA with Linear Models

## STAT206-Final-Project Due: 12/13/2024

## Group Members

-   Maile Kamada
-   Kevin Sanford
-   Harshaan Sall

## Summary

We intend to use linear regression techniques to approach the exercise in the Kaggle competition found at 
[https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data). 
The exercise provides a large data sets that describes houses in Ames, Iowa with 79 parameters. The goal of 
the exercise is to create an algorithm that predicts the selling price of homes based on the parameters. The 
data provided consists of two data sets: test.csv and train.csv. The training data set includes housing prices 
to facilitate the creation of a linear regression model that predicts sale prices of homes, which can then be 
tested on the test data set. Before using the test data set, we will attempt to maximize the accuracy of the 
model by splitting the training data in half, using half of the data for training, then comparing the other 
half with the model's prediction. After tuning the model, we will retrain it on the full training data set and 
predict housing prices for the test data set.

## Required Packages

-   base R packages
-   tidyverse

## Acknowledgments

-   [Kaggle Dataset](https://www.kaggle.com/datasets/marcopale/housing/data)
-   [Kaggle Competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
-   [Sample Code Analysis](https://sjmiller8182.github.io/RegressionHousingPrices/analysis/data/)
