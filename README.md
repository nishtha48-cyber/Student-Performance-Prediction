# Student-Performance-Prediction
A Python-based data analysis and machine learning project exploring socio-economic impacts on student grades using Linear Regression.

Student Achievement Trends: Analysis & Prediction

This project explores the factors influencing students' academic performance using a dataset of 1,000 records. It involves a full data science pipeline, from exploratory data analysis (EDA) and statistical hypothesis testing to building a predictive model for mathematics scores.

## 📌 Project Objective

The goal of this project is to understand how demographic and socio-economic attributes—such as gender, parental education, lunch type, and test preparation—impact student scores in Math, Reading, and Writing.

## 🛠️ Tech Stack

Language: Python

Libraries:

Data Manipulation: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-Learn (Linear Regression)

Statistics: SciPy (t-tests)

## 📊 Workflow

1) Data Cleaning & Preprocessing:

  Handled categorical data using One-Hot Encoding (nominal) and Label Encoding (ordinal).

  Treated outliers using the Interquartile Range (IQR) technique.

  Normalized features using StandardScaler to ensure equal contribution to the model.

2) Exploratory Data Analysis (EDA):

  Created histograms, boxplots, and violin plots to understand distributions.

  Generated a Correlation Heatmap to identify relationships between variables.

3) Hypothesis Testing:

  Performed an independent samples t-test to statistically prove the impact of test preparation courses on student outcomes.

4) Predictive Modeling:

  Developed a Linear Regression model to predict Math scores based on reading/writing performance and demographic factors.

  Evaluated the model using R-squared, RMSE, and MAE.

## 💡 Key Insights

Holistic Ability: There is a very strong correlation ( R>0.80 ) between math, reading, and writing scores.

Socio-economic Impact: Students with standard lunch types consistently outperformed those with free/reduced lunch.

Test Prep works: Statistical testing (p-value  < 0.05) confirmed that completing a test prep course significantly boosts math scores.

Parental Influence: A positive correlation exists between parental education levels and student performance.

## 📂 Dataset

The dataset StudentsPerformance.csv was sourced from Kaggle. It contains 1,000 records with 8 attributes.


