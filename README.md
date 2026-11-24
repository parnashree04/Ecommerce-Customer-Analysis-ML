# E-Commerce Customer Analysis Using Python and Machine Learning

## Project Overview
This project focuses on analyzing e-commerce customer behavior using Python and Machine Learning. It aims to understand customer purchasing patterns, predict customer spending, classify recent purchase behavior, and segment customers based on their shopping activities.

## Objectives
- Analyze customer purchasing behavior.
- Predict customer spending using regression models.
- Classify recent purchase behavior using classification models.
- Segment customers into meaningful groups using K-Means clustering.
- Compare the performance of different machine learning algorithms.

## Dataset
The dataset contains 350 customer records and 11 original features, including:
- Customer ID
- Gender
- Age
- City
- Membership Type
- Total Spend
- Items Purchased
- Average Rating
- Discount Applied
- Days Since Last Purchase
- Satisfaction Level

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Machine Learning

## Machine Learning Models

### 1. Customer Spending Prediction (Regression)
Algorithms:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

Evaluation metrics: MAE, MSE, RMSE, and R² Score.

### 2. Recent Purchase Behavior Classification
Algorithms:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

The target variable is based on whether a customer made a purchase within the last 30 days.

### 3. Customer Segmentation (Clustering)
Algorithm: K-Means Clustering

Customers are grouped into three segments:
- Premium
- Regular
- Occasional

StandardScaler is used for feature scaling.

## Project Workflow
1. Data loading
2. Data cleaning and preprocessing
3. Exploratory Data Analysis (EDA)
4. Data visualization
5. Feature encoding and scaling
6. Machine Learning model training
7. Model evaluation and comparison
8. Customer segmentation

## How to Run
1. Download the notebook from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload the `.ipynb` notebook.
4. Make sure the dataset CSV is available in your Google Drive at the path used in the notebook.
5. Run the notebook cells in order.

## Project Outcome
The project demonstrates how machine learning techniques can be applied to e-commerce customer data to understand spending patterns, classify recent purchasing activity, and identify customer segments.

## Author
**Parnashree Sinha**

MCA Student | Brainware University
