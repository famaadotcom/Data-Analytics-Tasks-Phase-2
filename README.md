**Data-Science-Analytics_Internship_Tasks_PHASE-2**
Bank Marketing Prediction Project Task Objective The objective of this project is to predict whether a customer will subscribe to a term deposit based on their personal and campaign-related information. The task focuses on handling an imbalanced dataset and building a model that can accurately identify potential customers.

**Approach**

Data Preprocessing • Loaded and explored the dataset • Handled missing values (if any) • Encoded categorical variables • Checked class imbalance in the target variable
Feature Selection • Selected relevant features affecting customer decisions • Removed unnecessary or redundant columns
Train-Test Split • Split the dataset into training and testing sets (80/20 ratio)
Model Building • Implemented: o Logistic Regression o Random Forest Classifier
Model Evaluation • Used metrics: o Accuracy o Precision o Recall o F1-score
Model Explainability • Applied SHAP • Identified important features influencing predictions
Results and Findings • The dataset was highly imbalanced, with most customers not subscribing • Random Forest outperformed Logistic Regression, especially in terms of F1-score • Logistic Regression struggled to capture complex relationships • SHAP analysis revealed key influencing features such as:

o Duration of contact o Previous campaign outcomes o Number of contacts
