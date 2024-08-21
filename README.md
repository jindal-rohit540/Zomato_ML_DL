# Zomato Success Predictor


# **Topics:** 
- ### Machine Learning 
- ### Deep Learning
- ### Statistics

## Overview

This project aims to predict whether a restaurant in Bangalore will be a success or failure based on various features using multiple machine learning models. The project also includes cross-validation and hypothesis testing to compare the performance of different models. Finally, a deep learning neural network (DNN) was implemented, with the conclusion that deep learning is not always the best approach.

## Project Description

- **Binary Classification:** The goal was to predict success based on the ratings of over 50,000 Zomato-registered restaurants in Bangalore.
- **Exploratory Data Analysis (EDA):** Extensive EDA was conducted, including data pre-processing, transformation, and feature engineering.
- **Geographical Analysis:** GeoPy was used for geographical analysis, leveraging latitude and longitude data to create a heatmap of restaurant clusters.
- **Model Selection:** Among six models, the top three performers were selected—K-Nearest Neighbors, Decision Tree, and Random Forest. These models achieved peak accuracy and F1 scores of 83% and 82%, respectively.
- **ROC Curve and Decision Threshold:** The ROC curve was plotted, and the decision threshold was adjusted for a lower false positive rate.
- **Hypothesis Testing:** Statistical methods such as Paired T-test, ANOVA, and McNemar test were applied for hypothesis testing to compare the models' performance.
- **Deep Learning Implementation:** A Sigmoid Deep Neural Network with Dropout regularization and Early stopping was built, achieving a 76% accuracy. However, it was concluded that deep learning did not outperform the traditional machine learning models in this case.

## Key Features

- **Data Analysis:** Comprehensive EDA, data transformation, and feature engineering.
- **Geospatial Analysis:** Heatmap creation using geographical data.
- **Model Comparison:** Cross-validation and hypothesis testing for model evaluation.
- **Deep Learning:** Implementation of a DNN with performance analysis against traditional models.

## Conclusion

The project demonstrates that while deep learning neural networks are powerful, they are not always the best choice, especially when traditional machine learning models perform better with less complexity.
