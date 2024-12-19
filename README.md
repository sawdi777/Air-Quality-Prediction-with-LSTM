# PM2.5 Prediction in Tehran Using Remote Sensing and Machine Learning

## Overview

This project aims to predict the concentration of **PM2.5** (fine particulate matter) in **Tehran**, Iran, utilizing **remote sensing data** and **advanced machine learning techniques**. PM2.5 levels are a critical indicator of air quality, with significant health implications for urban populations. By accurately forecasting PM2.5 concentrations, city planners and policymakers can make informed decisions to improve air quality and public health.

---

## Project Description

We developed predictive models for **daily and monthly PM2.5 levels** using various environmental and traffic-related data sources. The key steps involved in this project are:

- **Data Collection**: Gathered remote sensing data, meteorological information, and traffic-related variables for Tehran.
- **Data Preprocessing**: Cleaned and processed the data, handling missing values, outliers, and scaling features.
- **Feature Engineering**: Created lag features, rolling statistics, and temporal variables to capture trends and patterns in the data.
- **Modeling**: Implemented machine learning models such as **XGBoost** and **Long Short-Term Memory (LSTM)** neural networks for forecasting PM2.5 levels.
- **Evaluation**: Evaluated model performance using metrics like **RMSE (Root Mean Squared Error)**, **MAE (Mean Absolute Error)**, and **R² (Coefficient of Determination)**.


---

## Dataset


The Dataset for this project can be accessed in this kaggle Dataset. We published many more info about the Dataset and it's validity in the Kaggle Link below:
https://www.kaggle.com/datasets/sawdi777/tehran-air-quality-full-sat-traffic-metrology

---
## Results


The models achieved **exceptional performance**, particularly with the **LSTM neural network**:

- **Daily Predictions**: Achieved an **R² score greater than 0.99**, meaning over 99% of the variance in daily PM2.5 levels was explained by the model.
- **Monthly Predictions**: The model showed strong predictive accuracy, useful for long-term air quality planning.

These results validate the effectiveness of combining **remote sensing data** with **machine learning techniques** for accurate air quality forecasting.

---

## Conclusion

This project demonstrates the potential of **remote sensing and machine learning** to predict **PM2.5 concentrations** in Tehran. The high accuracy of the models indicates their potential for future predictions and assisting in strategic planning to improve air quality. The methodologies developed can be applied to other urban areas facing similar challenges with air pollution.

---

## Run the Notebooks:

Navigate to the notebooks/ directory and run the Jupyter notebooks to see the data processing and model training steps.

---

## Dependencies

Python 3.7+
pandas
numpy
scikit-learn
xgboost
tensorflow
matplotlib
seaborn
