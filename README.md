# ML-lead_scoring_case_study
Lead Scoring Case Study
 Project Overview

This project focuses on building a Lead Scoring Model to identify potential customers who are most likely to convert into paying customers.

The objective is to help the sales team prioritize high-quality leads and improve overall conversion rates using Machine Learning techniques.

 Business Objective

An education company wants to:

Identify Hot Leads

Improve lead conversion rate

Increase sales efficiency

Reduce time spent on low-quality leads

This project builds a Logistic Regression Model to assign a probability score to each lead.

 Dataset Description

The dataset contains information such as:

Lead Source

Total Time Spent on Website

Total Visits

Last Activity

Specialization

Current Occupation

What is your current occupation

Tags

City

Converted (Target Variable: 0 = No, 1 = Yes)

 Project Workflow
1️ Data Understanding

Loaded dataset

Checked shape, columns, and missing values

Identified target variable (Converted)

2️ Data Cleaning

Removed columns with high missing values

Handled null values

Converted categorical variables

Dropped irrelevant columns (e.g., IDs)

3️ Exploratory Data Analysis (EDA)

Checked distribution of variables

Analyzed relationship between features and conversion

Identified important predictors

Checked class imbalance

4️ Feature Engineering

Dummy variable creation

Handling multicollinearity

Scaling numerical variables

5️ Model Building

Train-Test Split

Logistic Regression Model

Feature Selection using:

p-values

VIF (Variance Inflation Factor)

6️ Model Evaluation

Confusion Matrix

Accuracy

Precision

Recall

F1 Score

ROC Curve

AUC Score

Cutoff optimization

 Model Performance

Achieved good balance between precision and recall

Optimized cutoff to improve business performance

Model effectively identifies high-converting leads

 Key Insights

Time spent on website strongly impacts conversion

Certain lead sources generate better quality leads

Occupation and last activity significantly affect conversion

Proper cutoff selection improves business decision-making

 Business Recommendation

Focus marketing efforts on high-probability leads

Use model score to prioritize calling strategy

Reduce cost spent on low conversion leads

 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Statsmodels



Author

Vaibhavi Khamkar


Data Analyst | Machine Learning Enthusiast
