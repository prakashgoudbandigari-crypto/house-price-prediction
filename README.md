# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting residential house prices using Machine Learning techniques on the King County Housing Dataset. The objective is to analyze housing features such as living area, number of bedrooms, bathrooms, location, and property grade to build accurate predictive models for estimating house prices.

The project demonstrates a complete end-to-end Data Science workflow including data exploration, preprocessing, visualization, model development, and performance evaluation.

---

## 🎯 Business Problem

A Real Estate Investment Trust (REIT) wants to estimate the market value of residential properties based on various housing characteristics. Accurate price prediction helps investors make informed decisions when purchasing and selling properties.

---

## 📊 Dataset Information

**Dataset:** King County House Sales Dataset

* Total Records: **21,613**
* Total Features: **21**
* Missing Values: **0**
* Target Variable: **price**

### Key Features

* Bedrooms
* Bathrooms
* Square Footage Living Area (`sqft_living`)
* Square Footage Lot (`sqft_lot`)
* Floors
* Waterfront
* View
* Condition
* Grade
* Square Footage Above Ground
* Square Footage Basement
* Year Built
* Latitude & Longitude
* Nearby Living Area (`sqft_living15`)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 📈 Project Workflow

### 1. Data Collection

* Loaded housing dataset
* Inspected dataset structure

### 2. Data Understanding

* Checked data types
* Analyzed dataset dimensions
* Verified data quality

### 3. Data Cleaning

* Checked missing values
* Verified dataset consistency

### 4. Exploratory Data Analysis (EDA)

* Statistical summary
* Correlation analysis
* Feature relationship analysis
* Data visualization

### 5. Model Development

* Simple Linear Regression
* Multiple Linear Regression
* Polynomial Regression
* Machine Learning Pipeline

### 6. Model Evaluation

* R² Score
* Train/Test Split Validation
* Model Comparison

---

## 📊 Correlation Analysis

Top features correlated with house price:

| Feature       | Correlation |
| ------------- | ----------- |
| sqft_living   | 0.702       |
| grade         | 0.667       |
| sqft_above    | 0.606       |
| sqft_living15 | 0.585       |
| bathrooms     | 0.525       |

The living area (`sqft_living`) showed the strongest relationship with house prices.

---

## 🤖 Models Implemented

### Simple Linear Regression

Using:

* sqft_living

**R² Score:** 0.4929

---

### Multiple Linear Regression

Features Used:

* floors
* waterfront
* lat
* bedrooms
* sqft_basement
* view
* bathrooms
* sqft_living15
* sqft_above
* grade
* sqft_living

**R² Score:** 0.6577

---

### Train-Test Evaluation

Training R² Score: **0.7015**

Testing R² Score: **0.6904**

The model demonstrated good generalization with minimal overfitting.

---

### Polynomial Regression

Degree: **2**

Testing R² Score: **0.5208**

---

### Pipeline Model

Components:

* StandardScaler
* PolynomialFeatures
* LinearRegression

**R² Score:** 0.8300

---

## 🏆 Model Performance Comparison

| Model                        |   R² Score |
| ---------------------------- | ---------: |
| Simple Linear Regression     |     0.4929 |
| Multiple Linear Regression   |     0.6577 |
| Linear Regression (Test Set) |     0.6904 |
| Polynomial Regression        |     0.5208 |
| Pipeline Model               | **0.8300** |

---

## 🔑 Key Findings

* Living area is the strongest predictor of house price.
* Multiple features improve prediction accuracy significantly.
* The Pipeline Model achieved the highest performance.
* The final model explains approximately 83% of the variation in house prices.

---

## 🚀 Future Improvements

* Feature Engineering
* Hyperparameter Tuning
* Cross Validation
* XGBoost Regression
* Random Forest Regression
* Streamlit Web Application Deployment
* Power BI Dashboard Integration

---

## 📷 Project Screenshots

Add screenshots of:

* Correlation Analysis
* Regression Plots
* Model Comparison Results
* Jupyter Notebook Outputs

---

## 👨‍💻 Author

**Prakash Goud**

Aspiring Data Scientist | Machine Learning Enthusiast | Python Developer

GitHub: https://github.com/prakashgoudbandigari-crypto

---

## ⭐ Conclusion

The House Price Prediction project successfully applied Machine Learning techniques to estimate residential property prices. Among all models tested, the Pipeline Model delivered the best performance with an R² score of 0.83, making it the most suitable model for predicting house prices in this dataset.
