# Wildfire-Prediction
This repository contains my solution for Zindi's Wildfire Prediction Challenge, where I ranked 27th out of 82 and the best from Uganda. It includes data wrangling, feature engineering, and the development of machine learning models like Random Forest, Gradient Boosting, and a Stacking Regressor ensemble to predict wildfire burn areas.

This repository contains the code and resources for the Wildfire Prediction Challenge hosted on Zindi. The objective of this challenge was to create a machine-learning model capable of predicting the burned area in different locations over 2014 to 2016.

## Project Overview

Each year, thousands of fires blaze across Africa, some of which are natural and beneficial to ecosystems, while others are destructive wildfires. This project aims to develop a machine-learning model to predict burned areas across Zimbabwe from 2014 to 2016, based on historical data from 2001 to 2013. By analyzing factors such as rainfall, temperature, and land cover, the model helps understand fire dynamics and predicts future burn areas, aiding in managing their environmental and climatic impacts.

## Dataset

The dataset used in this project is provided by the Zindi platform. It includes:

- `Train.csv`: The training data with features and the target variable (`burn_area`).
- `Test.csv`: The test data for which the predictions need to be made.

## Models Used

Several models were developed and evaluated in this project:

1. **K-Nearest Neighbors (KNN) Regressor**
2. **Random Forest Regressor**
3. **Gradient Boosting Regressor**
4. **Stacking Regressor** (Combining KNN, Random Forest, and Gradient Boosting)

## Results

The best-performing model was a stacked regressor, which combined the predictions of multiple models to improve accuracy. The final RMSE on the test set was 0.019879952 on the Zindi Leaderboard


