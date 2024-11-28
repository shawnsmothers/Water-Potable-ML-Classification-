# Water-Potable-ML-Classification-

## Description

Welcome to the **Water Potability Classification** project! This repository focuses on building a machine learning model to classify whether water is potable (safe to drink) or not. Below, you'll find an overview of the project's features, methods, and how to use it.

---

## Project Overview

This project uses a supervised machine learning approach to classify water samples as potable or non-potable based on various physical and chemical properties. It provides insights into the data through **exploratory data analysis (EDA)** and a robust machine learning pipeline.

---

## Key Features:

### **Data Exploration and Visualization:**
- Created a **correlation matrix** to explore relationships between features and the target variable.

### **Pipeline for Model Evaluation:**
- Built a pipeline to test different classification models, such as **Random Forest**, **Logistic Regression**, and **Support Vector Machines**.
- Selected **Logistic Regression Classifier** based on performance metrics. Accurcy Score resulted in 0.66       

### **Hyperparameter Tuning:**
- Performed hyperparameter optimization using **RandomizedSearchCV** to improve model accuracy.

### **Model Deployment with Pickle:**
- Exported the trained model using **pickle** for user interaction.
- Users can input water parameters to determine whether the water is safe to drink or not.
