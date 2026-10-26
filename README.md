# 🏠 Airbnb NYC 2019 – Price Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) and predicting Airbnb listing prices in New York City using Machine Learning.

The Airbnb NYC 2019 dataset is analyzed using Python to identify pricing patterns, handle missing values, remove outliers, and build a Linear Regression model.

## 🎯 Project Objectives

- Perform Exploratory Data Analysis (EDA).
- Identify and handle missing values.
- Detect and remove outliers.
- Perform Univariate, Bivariate, and Multivariate Analysis.
- Apply feature selection and One-Hot Encoding.
- Train a Linear Regression model.
- Evaluate model performance using R², MAE, MSE, and RMSE.
- Analyze actual versus predicted prices.

## 📊 Dataset Information

**Dataset Name:** Airbnb NYC 2019

**Total Rows:** 48,895

**Total Columns:** 16

**Target Variable:** Price

The dataset contains Airbnb listing information such as neighbourhood, room type, price, minimum nights, availability, and customer reviews.

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🔍 Project Methodology

### Step 1: Exploratory Data Analysis
- Dataset inspection using `head()`, `tail()`, and `describe()`.
- Checking duplicates and missing values.
- Univariate, Bivariate, and Multivariate Analysis.

### Step 2: Data Cleaning
- Handle missing values.
- Remove irrelevant columns.
- Prepare the dataset for machine learning.

### Step 3: Outlier Treatment
- Detect outliers using boxplots.
- Remove extreme values using the 95th percentile method.

### Step 4: Feature Engineering
- Drop high-cardinality features.
- Apply One-Hot Encoding to categorical variables.

### Step 5: Train-Test Split
- Training Data: 80%
- Testing Data: 20%
- Random State: 42

### Step 6: Model Training and Evaluation
Train a Linear Regression model and evaluate its performance using:

- R-Squared (R²)
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

### Step 7: Residual Analysis
- Actual vs. Predicted Price Scatter Plot
- Residual Plot
- Comparison of prediction errors for cheap and expensive listings

## 📈 Visualizations

The project includes:

- Price Distribution Histogram
- Room Type Distribution
- Neighbourhood Group Distribution
- Room Type vs. Price
- Neighbourhood Group vs. Price
- Correlation Heatmap
- Actual vs. Predicted Prices
- Residual Analysis

## 🚀 How to Run the Project

1. Download or clone this GitHub repository.
2. Open the Jupyter Notebook (`.ipynb`) in Google Colab.
3. Upload the Airbnb NYC 2019 dataset.
4. Run the notebook cells sequentially.
5. View the EDA visualizations, model predictions, and evaluation metrics.

## 📝 Conclusion

This project demonstrates the complete machine learning workflow for Airbnb price prediction, including data preprocessing, exploratory analysis, feature engineering, model training, and evaluation.

The Linear Regression model provides a baseline for understanding how listing characteristics relate to Airbnb prices. Its accuracy and limitations can be assessed using evaluation metrics and residual plots.

## 📚 Project Category

**Artificial Intelligence and Machine Learning (AIML) – Minor Project**

**Dataset:** Airbnb NYC 2019

**Algorithm:** Linear Regression

**Platform:** Google Colab
