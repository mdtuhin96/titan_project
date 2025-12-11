Project Overview

The goal of this project is to analyze the Titanic dataset and build predictive models that determine whether a passenger survived based on their characteristics such as age, gender, class, fare, and family size.

 Data Preprocessing
 Data Cleaning

Handled missing values

Age → filled using median

Fare → filled using median

Embarked → filled using mode

Removed duplicate entries

Dropped irrelevant columns:
PassengerId, Name, Ticket, Cabin

Converted data into correct types

✔ Encoding

Label Encoding for binary feature Sex

One-Hot Encoding for Embarked

✔ Feature Scaling

Applied StandardScaler for feature normalization

✔ Train-Test Split

80% training data

20% testing data

🤖 Machine Learning Models Used
Algorithm	Purpose
Logistic Regression	Baseline linear classification
K-Nearest Neighbors (KNN)	Distance-based classification
Decision Tree	Rule-based decision model
Random Forest	Ensemble of multiple decision trees
Support Vector Machine (SVM)	Margin-based classifier
