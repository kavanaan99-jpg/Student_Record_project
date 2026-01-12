# Capstone Project – Pandas + Prediction

## Student Details
Name: Kavana A N  
USN: 1BG24BA051  
Course: AI and ML for Financial Services  

## Project Title
Hospital Outpatient Data Analysis and Prediction using Pandas

## Objective
The objective of this project is to build a complete data-to-decision workflow using Pandas and basic machine learning techniques. The project focuses on cleaning real-world hospital outpatient data, generating insights, and building predictive models for both numeric and categorical outcomes.

## Dataset Description
The dataset used is the Hospital Outpatient Dataset provided during class.

Each row in the dataset represents a single outpatient visit to the hospital, including patient demographics, visit details, billing information, and follow-up requirements.

### Example Columns
- Age: Age of the patient
- Gender: Gender of the patient
- Visit_Date: Date of outpatient visit
- Diagnosis: Medical diagnosis
- Medicine_Cost: Cost of medicines prescribed
- Consultation_Fee: Doctor consultation fee
- Total_Bill: Total amount billed to the patient
- Followup_Required: Whether follow-up is required (Yes/No)

## Tools and Libraries Used
- Python
- Pandas
- scikit-learn
- Jupyter Notebook

## Project Tasks Performed
1. Loaded and audited the dataset using Pandas
2. Cleaned the dataset by fixing data types, handling missing values, text cleaning, and removing duplicates
3. Performed feature engineering by creating new derived and conditional columns
4. Generated insights using groupby, aggregation, sorting, and value counts
5. Built a Linear Regression model to predict Total Bill
6. Built a Logistic Regression model to predict Follow-up Requirement
7. Summarized insights, model performance, and limitations

## Machine Learning Models Used
- Linear Regression (Numeric prediction)
- Logistic Regression (Binary classification)

## Evaluation Metrics
- Mean Absolute Error (MAE) for regression
- Confusion Matrix, Precision, and Recall for classification

## Key Results
- The regression model predicts hospital bills with reasonable accuracy.
- The classification model effectively identifies patients requiring follow-up.
- Recall is emphasized to reduce the risk of missing critical follow-up cases.

## Conclusion
This project demonstrates effective use of Pandas for data cleaning, feature engineering, and exploratory analysis, along with basic predictive modeling using scikit-learn. While the models perform reasonably well, accuracy could be improved with additional clinical features and larger datasets.

## Files Included
- 1BG24BA051_Kavana A N.ipynb
- Hospital Outpatient Dataset (CSV)
- README.md
