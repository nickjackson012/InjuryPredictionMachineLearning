# Athlete ACL Injury Prediction Model
## Overview
An ML-based tool designed to identify athletes at risk of ACL tears, helping enable early intervention and injury prevention.
The model uses factors such as 'ACL_Risk_Score', 'Fatigue_Score', and 'Training_Intensity', along with other biometric data to make its prediction.
The model will return the probability of an ACL injury and classifies the athlete as 'Low Risk', 'Medium Risk', or 'High Risk'.

## The Process
This project was developed during a 4 week collaboration with the Biotech Club at The University of Texas at Dallas. Through the direction of a student lead, I was introduced to Machine Learning concepts and gained hands on experience on how to develop a working model. The goal was to explore the intersection of sports science and machine learning by building predictive models for injury risk. During this process, multiple models were implemented and evaluated, including:
- Decision Tree
- Logistic Regression
- Support Vector Machines
- K-Nearest Neighbors

At the end of the process, we discussed the advantages and disadvantages of the various models, and how a false negative in injury prediction can be more costly than a false positive prediction. We used the Logistic Regression model for our final model due to the smaller gap between Test and Training accuracy. It was an excellent introduction to such powerful tools for analyzing data.

## Tools and Frameworks
- Python
- Google Colab: cloud-based development environment
- Pandas & Numpy: data cleaning and analysis
- Scikit-learn: preprocessing, modeling, and evaluation
- Matplotlib & Seaborn: data visualization

## How It Works
1) Data is cleaned and preprocessed
2) Features are properly scaled using StandardScalar
3) The Logistic Regression Model is trained on 80% of the dataset
4) Hyperparameters are optimized using GridSearchCV
5) Final model displays athlete injury probability and classifies risk
