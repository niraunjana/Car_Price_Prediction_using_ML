# Car_Price_Prediction_using_ML

## Project Overview

Car price prediction is a popular application of machine learning, addressing the problem of estimating a car's price based on its attributes. The price of a car depends on several factors such as:

-- The brand's goodwill.

-- Features and specifications (e.g., horsepower, engine type, and fuel efficiency).
-- Mileage and performance.
-- Age of the car and other market trends.

This project focuses on developing a machine learning pipeline to predict car prices accurately. By leveraging various regression algorithms, we analyze and model the relationships between car attributes and their prices.


## Project Objectives

### Understand the Problem: 
Analyze the factors influencing car prices and their importance in prediction.

### Data Preparation: 
Process and clean the data for effective model training.

### Model Development:
Train and compare multiple regression models to identify the best-performing one.

### Evaluation: 
Evaluate the models using appropriate metrics like R² score, Mean Absolute Error (MAE), and Mean Squared Error (MSE).

### Visualization and Insights: 

Visualize feature importance and prediction results to provide actionable insights.

### Machine Learning Models Used

### Random Forest Regressor:
A popular ensemble method that builds multiple decision trees and averages their results for robust predictions.

### Decision Tree Regressor:
A simple, interpretable algorithm that splits the data into subsets based on feature thresholds.

### Linear Regression (Baseline): 
Used as a benchmark to compare the performance of other models.

## Project Workflow

### Data Collection:

-- Use publicly available car price datasets (e.g., Kaggle, UCI, or other sources).

-- Include attributes such as car brand, model, year of manufacture, horsepower, fuel type, mileage, and price.

### Data Cleaning and Preprocessing:

-- Handle missing values and outliers.

-- Encode categorical variables (e.g., car brand and fuel type) using techniques like One-Hot Encoding or Label Encoding.

-- Normalize/scale numerical features to improve model performance.

### Exploratory Data Analysis (EDA):

-- Analyze the relationships between features and car prices using correlation matrices and scatter plots.

-- Visualize distributions of numerical and categorical features.

### Feature Selection:

-- Identify the most relevant features for prediction using techniques like correlation analysis and feature importance.

### Model Training and Comparison:

-- Split the dataset into training and testing sets.

-- Train each machine learning model (XGBoost, KNN, Random Forest, Decision Tree, Linear Regression).

-- Perform hyperparameter tuning (e.g., Grid Search, Random Search) to optimize model performance.

### Evaluation:

-- Evaluate all models using metrics such as R², MAE, MSE, and RMSE.

-- Compare their performance to identify the best model for predicting car prices.

### Visualization and Insights:

-- Create visualizations to showcase:

-- Feature importance for models like XGBoost and Random Forest.

-- Actual vs. predicted car prices.

-- Model comparison based on evaluation metrics.


## Key Features

-- Implementation of multiple machine learning models for car price prediction.

-- Comprehensive comparison of model performance.

-- Insightful visualizations to interpret the results and model predictions.

## Data Visualization 


![image](https://github.com/user-attachments/assets/dad86fd9-d8a7-49e9-be94-d0b411afdf42)


![image](https://github.com/user-attachments/assets/30f9bb8e-34a3-4586-86a2-90d76e6d997a)


![image](https://github.com/user-attachments/assets/f424d196-fc4e-445e-aa0a-98c656d21d2d)


![image](https://github.com/user-attachments/assets/d928ebef-4ac1-47c9-a379-7f6e0383117f)


![image](https://github.com/user-attachments/assets/9207c962-19fa-44e8-b461-06389572789f)


![image](https://github.com/user-attachments/assets/1519dd42-f17d-4b79-99ac-9dfcb6113508)


![image](https://github.com/user-attachments/assets/ec922d7c-da93-4985-8ac9-9f662ff55271)


![image](https://github.com/user-attachments/assets/609fdea0-667a-46c1-b118-fddacabc0a81)


![image](https://github.com/user-attachments/assets/28f90a67-608e-4866-a6d8-41d9b34f4bc0)


![image](https://github.com/user-attachments/assets/500be9e6-5a7a-4e73-877c-541031acfaef)

### Comparison

![image](https://github.com/user-attachments/assets/1298657b-1435-4296-8143-1d3960dd5afa)


## Results and Conclusion

The project evaluates the performance of various models, demonstrating their strengths and limitations in predicting car prices. Models like XGBoost and Random Forest typically outperform others due to their ability to handle complex relationships and non-linear data.
