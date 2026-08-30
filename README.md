# Student Performance Machine Learning Project

## Project Overview

This project analyzes student performance data and applies machine learning techniques to understand and predict academic performance.

The project follows a complete machine learning workflow:

* Exploratory Data Analysis (EDA)
* Data preprocessing
* Linear Regression for predicting `exam_score`
* Classification for predicting Pass/Fail
* Model evaluation
* Training vs Testing performance comparison
* Identification of important factors affecting student performance

## Dataset

The dataset contains information about students' study habits, attendance, sleep, social media usage, Netflix usage, exercise, mental health, and other factors related to academic performance.

**Target variable for Regression:**

* `exam_score`

**Target variable for Classification:**

* `pass_fail`

Students are classified as:

* **Pass:** `exam_score >= 50`
* **Fail:** `exam_score < 50`

## Exploratory Data Analysis

The EDA includes:

* Dataset structure and summary statistics
* Identification of numerical and categorical variables
* Missing value analysis
* Distribution of exam scores
* Potential outlier detection using the IQR method
* Correlation analysis
* Relationships between student habits and exam scores

## Machine Learning Models

### 1. Linear Regression

Linear Regression is used to predict students' `exam_score` using relevant features such as:

* Study hours per day
* Attendance percentage
* Sleep hours
* Social media hours
* Netflix hours
* Exercise frequency
* Mental health rating
* Other suitable variables in the dataset

The model is evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### 2. Logistic Regression

Logistic Regression is used to classify students into:

* Pass
* Fail

The classification model is evaluated using:

* Confusion Matrix
* Accuracy
* Precision
* Recall
* F1-Score

## Key Findings

The analysis shows that study time has the strongest positive relationship with exam scores. Mental health rating also has a positive relationship with performance, while higher social media and Netflix usage show negative relationships with exam scores.

The regression and classification models show similar training and testing performance, indicating no strong evidence of overfitting.

## Project Files

* `Student_Performance_ML_Project.ipynb` — Complete analysis and machine learning notebook
* `Day18_19_student_habits_performance.csv` — Student Performance dataset

## Conclusion

The project demonstrates how exploratory data analysis and machine learning can be used to understand student performance and identify factors associated with academic success.
