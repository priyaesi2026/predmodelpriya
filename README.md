"# predmodelpriya" 
House Price Prediction using Machine Learning

Project Overview

This project focuses on predicting house prices using various house-related features such as living area, number of bedrooms, bathrooms, floors, house age, distance from city, and quality score. The dataset is preprocessed and used to build a machine learning model for accurate house price prediction.

Dataset Information

Dataset Name: House Prices Dataset

Total Records: 1000

Total Features: 8

Features Description

Feature| Description
sqft_living| Living area of the house (square feet)
bedrooms| Number of bedrooms
bathrooms| Number of bathrooms
floors| Number of floors
house_age| Age of the house (years)
dist_to_city_km| Distance from city center (km)
quality_score| Overall quality rating of the house
price| Target variable (House Price)

Data Preprocessing

The following preprocessing steps were performed:

1. Loaded the dataset using Pandas.
2. Checked dataset shape and structure.
3. Identified missing values.
4. Handled missing values in the bathrooms column.
5. Verified data types of all features.
6. Prepared data for machine learning model training.

Missing Values Summary

Column| Missing Values
bathrooms| 12
Other Columns| 0

Exploratory Data Analysis

Basic statistical analysis was performed to understand the dataset characteristics.

Key Observations

- Average living area: 1872 sq.ft.
- Average bedrooms: 3
- Average bathrooms: 2.5
- Average house age: 19 years
- Dataset contains houses with varying quality scores and distances from the city.

Machine Learning Approach

Algorithm Used

Linear Regression

Linear Regression was selected because:

- House price is a continuous numerical value.
- Regression algorithms are suitable for price prediction tasks.
- It provides interpretable and efficient predictions.

Workflow

1. Import Required Libraries
2. Load Dataset
3. Data Cleaning
4. Handle Missing Values
5. Feature Selection
6. Train-Test Split
7. Model Training
8. Prediction
9. Model Evaluation

Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Google Colab / Jupyter Notebook

Project Outcome

The model learns relationships between house characteristics and their prices, allowing it to predict house prices for new properties based on their features.

Conclusion

This project demonstrates the complete machine learning workflow for house price prediction, including data preprocessing, feature analysis, model training, and prediction. It provides practical experience in handling real-world datasets and implementing regression-based machine learning solutions.
