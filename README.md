# Loan Approval Prediction using Machine Learning

## Project Overview

This project builds a **Machine Learning model to predict whether a loan application should be approved or rejected** based on applicant financial and demographic information.

Financial institutions face risk when approving loans. This model helps analyze applicant data and estimate the likelihood of loan approval using classification algorithms.

---

## Problem Statement

Banks receive many loan applications, and manually evaluating each applicant can be time-consuming.
The objective of this project is to build a machine learning model that predicts **Loan Approval Status** based on features such as income, credit history, education, and property area.

Target Variable:

```
Loan_Status
```

Type of Problem:

```
Binary Classification
```

---

## Dataset Information

The dataset contains information about loan applicants including:

* Gender
* Married Status
* Dependents
* Education
* Self Employed
* Applicant Income
* Coapplicant Income
* Loan Amount
* Loan Amount Term
* Credit History
* Property Area
* Loan Status (Target Variable)

---

## Project Workflow

### 1. Data Loading

The dataset was loaded using Pandas and inspected to understand its structure and features.

### 2. Data Cleaning

Missing values were handled using:

* **Mode** for categorical variables
* **Median** for numerical variables

This ensures the dataset is complete and ready for modeling.

### 3. Exploratory Data Analysis (EDA)

EDA was performed to understand relationships between variables and loan approval status.
Visualizations were created to analyze distributions and patterns in the data.

### 4. Data Preprocessing

Categorical variables were converted into numerical values using **Label Encoding** so that machine learning models could process them.

### 5. Train-Test Split

The dataset was divided into training and testing sets to evaluate model performance on unseen data.

### 6. Model Training

Two machine learning algorithms were used:

* Logistic Regression
* Random Forest Classifier

### 7. Model Evaluation

Model performance was evaluated using:

* Accuracy Score
* Confusion Matrix
* Heatmap Visualization

---

## Key Insights

Some of the most important factors affecting loan approval include:

* Credit History
* Applicant Income
* Loan Amount
* Property Area

Applicants with a **good credit history** were significantly more likely to have their loans approved.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Skills Demonstrated

* Data Cleaning
* Handling Missing Values
* Exploratory Data Analysis
* Data Visualization
* Machine Learning Model Building
* Model Evaluation

---

## Project Structure

```
loan-approval-prediction-ml
│
├── loan_prediction.ipynb
├── loan_dataset.csv
├── README.md
└── LICENSE
```

---

## Future Improvements

* Hyperparameter tuning for improved accuracy
* Trying additional models such as Decision Trees or Gradient Boosting
* Feature engineering for better predictions
* Deploying the model using a web interface

---

## Author

Vansh Kumar
Aspiring Data Scientist | Machine Learning Enthusiast
