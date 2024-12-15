# Exploring Machine Learning Techniques for Heart Disease Prediction

## **Overview**
Heart disease is a leading cause of mortality worldwide, with early detection playing a crucial role in improving patient outcomes and optimizing healthcare resources. This project leverages machine learning (ML) to predict heart disease risk using behavioral, demographic, and clinical health indicators from the Behavioral Risk Factor Surveillance System (BRFSS) dataset.

The goal of this project is to develop and evaluate machine learning models to predict heart disease risk, prioritizing recall over precision using the F-beta score (\( \beta > 1\)) as the primary evaluation metric. This ensures models are tuned to minimize false negatives, reducing the likelihood of missing high-risk patients.

---

## **Repository Structure**
* data/ - Stores dataset
* figures/ - Stores all figures used in report and EDA
* report/ - Report of project 
* results/ - Trained models results on test set 
* src/ - Divided into EDA and Modelling where EDA includes data ingestion and general analysis and Modelling includes spliting, preprocessing, hyperparameter tuning and interpretation

--- 

**Key Packages of Project:**
* python                    3.12.5
* jupyter                   1.1.1
* matplotlib                3.9.2
* numpy                     1.26.4
* pandas                    2.2.2
* pickleshare               0.7.5
* pip                       24.2
* plotly                    5.23.0
* scikit-learn              1.5.1
* scipy                     1.14.1
* seaborn                   0.13.2
* shap                      0.45.1
* xgboost                   2.1.1
