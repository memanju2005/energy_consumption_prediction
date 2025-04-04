Energy Consumption Prediction using Simple Linear Regression

Overview

This notebook demonstrates the implementation of Simple Linear Regression to predict energy consumption based on a single independent variable. By analyzing historical data, the model helps forecast future energy usage, optimizing consumption patterns and improving efficiency.

Features

✔ Loads and explores energy consumption data

✔ Visualizes energy trends using scatter plots

✔ Splits data into training and testing sets

✔ Trains a Simple Linear Regression model

✔ Evaluates model performance using metrics like Mean Squared Error (MSE) and R² Score

✔ Plots the regression line to visualize predictions

Use Cases
This model can be applied to various energy-related scenarios, such as:

📌 Predicting electricity consumption based on temperature changes

📌 Estimating HVAC energy usage based on external weather conditions

📌 Forecasting appliance power consumption based on operational hours

📌 Optimizing energy efficiency in smart homes and buildings

Libraries Used

📌 NumPy – For numerical computations

📌 Pandas – For data handling and manipulation

📌 Matplotlib – For visualizing trends

📌 Scikit-learn – For building and evaluating the regression model

Dataset
The dataset consists of two key variables:

Independent Variable (X) – The predictor (e.g., temperature, appliance usage hours, occupancy levels)

Dependent Variable (Y) – The response variable, i.e., energy consumption (kWh)

Workflow

1️⃣ Import necessary libraries

2️⃣ Load and visualize the energy dataset

3️⃣ Preprocess the data (handle missing values if any)

4️⃣ Split the data into training and testing sets

5️⃣ Train the Simple Linear Regression model

6️⃣ Evaluate model performance

7️⃣ Visualize energy consumption predictions with a regression line

