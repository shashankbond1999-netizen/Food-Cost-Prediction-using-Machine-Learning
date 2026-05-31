# Food-Cost-Prediction-using-Machine-Learning
# Food Cost Prediction using Machine Learning

## Project Overview

This project predicts food procurement costs using Machine Learning techniques. The objective is to estimate procurement expenses based on transaction details such as units purchased, weight, vendor, distributor, agency, and product categories.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Random Forest Regressor
* Matplotlib
* Google Colab
* GitHub

## Dataset Information

* Total Records: 17,208
* Procurement transactions across multiple agencies
* Includes vendors, distributors, food categories, units purchased, weight, and total cost

## Problem Statement

Food procurement organizations need accurate cost estimation to support budgeting and purchasing decisions. This project uses historical procurement data to predict total procurement costs.

## Machine Learning Workflow

1. Data Loading and Exploration
2. Data Cleaning
3. Feature Selection
4. One-Hot Encoding of Categorical Variables
5. Train-Test Split
6. Random Forest Regression Model
7. Model Evaluation
8. Feature Importance Analysis

## Features Used

* Number of Units
* Total Weight in lbs
* Agency
* Vendor
* Distributor
* Food Product Group
* Food Product Category
* Product Type

## Target Variable

* Total Cost

## Model Used

* Random Forest Regressor

## Evaluation Metrics

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

## Feature Importance

![Feature Importance](feature_importance.png)

The feature importance chart highlights the key factors influencing procurement costs.

## Business Impact

* Supports procurement budgeting
* Improves cost forecasting accuracy
* Identifies major cost drivers
* Enables data-driven purchasing decisions

## Repository Contents

* food_procurement_cleaned.csv
* analysis.ipynb
* feature_importance.png
* README.md

## Author

Sai Shashank R

MBA – Business Analytics
CMS Business School, Jain (Deemed-to-be University)
