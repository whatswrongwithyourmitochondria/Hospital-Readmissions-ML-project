# Hospital-Readmissions-ML-project
This project aims to develop machine learning models to predict hospital readmissions. The project was a part of ML course (Data Science and Advanced Analytics master's program) at NOVA IMS.

The project focuses on two main tasks:

1. **Binary Classification**: Develop a model to predict if a patient will be readmitted to the hospital within 30 days of discharge. Accurate predictions can help healthcare providers implement preventive measures and timely interventions, potentially saving significant healthcare costs.
   
2. **Multiclass Classification**: Create a model to predict the timeframe of a patient's readmission, categorized as “No”, “<30 days”, or “>30 days”. This model provides deeper insights into patient risk levels, helping hospitals optimize post-discharge care and follow-up procedures.

## Project Goals
The main objective is to provide healthcare providers with predictive tools that enhance patient care quality, reduce readmission rates, and contribute to more sustainable healthcare spending.

## I. Introduction
Hospital readmissions are a major challenge in healthcare, affecting both care quality and financial costs. Readmissions shortly after discharge indicate potential care gaps and increase the financial burden on the healthcare system. This issue is particularly significant for diabetic patients, whose readmissions contribute substantially to overall costs. Predicting these readmissions can improve patient care and lead to significant cost savings.

## II. Project Goals
1. Develop a binary classification model to predict hospital readmissions within 30 days.
2. Create a multiclass classification model to predict the timeframe of hospital readmissions.

## III. Dataset
The project uses two datasets for training and testing. The training set includes features and target variables for building and validating the models. The test set includes the same descriptive attributes but lacks target variables, which will be used for final predictions.

### Dataset Attributes
- **Encounter Information**: Includes identifiers, demographic details (race, gender, age), health insurance codes, and visit history.
- **Medical Information**: Includes medical specialty, average pulse, discharge disposition, admission source, length of stay, lab tests, procedures, diagnoses, glucose and A1C test results, medication changes, and prescribed diabetes medications.
- **Targets**: Binary target for readmission within 30 days and a multiclass target for the timeframe of readmission.
