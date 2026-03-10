🧾 Fake Job Posting Prediction using Logistic Regression
📌 Project Overview

Online job portals contain thousands of job postings, but some of them are fraudulent or fake job advertisements created to scam applicants. This project aims to build a machine learning model that can detect fake job postings using Logistic Regression.

The model analyzes job-related features such as job title, company profile, description, requirements, and other attributes to classify whether a job posting is real or fraudulent.

This project is implemented using Python and Google Colab with common data science libraries.

🎯 Objectives

Detect fraudulent job postings using machine learning

Apply Logistic Regression for classification

Perform data preprocessing and feature engineering

Evaluate model performance using classification metrics

📂 Dataset

The dataset contains job posting information with various features such as:

Job Title

Location

Department

Salary Range

Company Profile

Job Description

Requirements

Benefits

Employment Type

Telecommuting

Fraudulent label (Target Variable)

Target Variable

0 → Real Job Posting

1 → Fake Job Posting

⚙️ Technologies Used

Python

Google Colab

Pandas – Data manipulation

NumPy – Numerical computation

Matplotlib / Seaborn – Data visualization

Scikit-learn – Machine learning model

🧠 Machine Learning Workflow
1️⃣ Data Loading

Import dataset using Pandas

Inspect dataset structure using:

.head()

.info()

.describe()

2️⃣ Data Preprocessing

Handle missing values

Convert categorical variables

Text processing for job descriptions

Feature selection

3️⃣ Exploratory Data Analysis (EDA)

Visualize distribution of real vs fake jobs

Analyze correlations between features

4️⃣ Model Building

The model used in this project:

Logistic Regression

Logistic Regression is a classification algorithm used to predict the probability of a binary outcome.

5️⃣ Model Training

Split dataset into training and testing sets

Train the Logistic Regression model on the training data

6️⃣ Model Evaluation

Model performance is evaluated using:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix
