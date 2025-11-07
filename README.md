# Death Analysis - Exploratory Data Analytics and Predictive Modelling
### CITS4009 Project: Computational Data Analysis | The University of Western Australia

**Objective**
This project explores global health data to uncover insights into causes of death across countries and to develop predictive models that classify and cluster countries by cause.  

---

## Project Overview
The analysis was conducted using **R** and focuses on:
- **Exploratory Data Analysis (EDA):** Understanding trends and relationships in the “Countries and Death Causes” dataset.  
- **Predictive Modelling:** Applying machine learning models to classify health outcomes and country groups.  
- **Interactive Visualization:** Creating a **Shiny App** for dynamic exploration of the results.

---

## Tools & Techniques  
| Category | Tools / Methods |
|-----------|----------------|
| Language | R, R Markdown, Shiny |
| Data Preparation | Data cleaning, transformation, missing value handling, feature selection |
| Visualisation | ggplot2, Shiny interactive dashboards |
| Modelling | Decision Tree, Logistic Regression, K-Means Clustering, Principal Component Analysis (PCA) |
| Evaluation | ROC Curves, Precision, Recall, F1 Score, Accuracy, WSS |

---

## Methodology Summary

### 1. Data Preparation  
- Cleaned and transformed the dataset by removing duplicates, handling missing values, and labelling categorical data.  
- Merged multiple data sources and ensured consistent formats.  

### 2. Exploratory Data Analysis  
- Visualised relationships between causes of death within different countries.  
- Identified high-correlation attributes influencing the number of deaths.  

### 3. Predictive Modelling  
- **Classification Models:**  
  Implemented **Decision Tree** and **Logistic Regression** models to predict mortality categories.  
  - Compared performance between full-feature and selected-feature models.  
  - Evaluated models using ROC curves, precision, recall, F1, and accuracy.  

- **Clustering Models:**  
  Built **K-Means clustering** models and visualised clusters on 2D PCA-reduced space.  
  - Determined optimal cluster number using the Elbow Method.  

---

## 📈 Results & Insights  
- Achieved strong classification performance (accuracy above 85%) using full features with the **Decision Tree** classification model.  
- PCA revealed meaningful country groupings by socio-economic and health similarity.  
- Interactive Shiny app enabled intuitive exploration of model outcomes and clusters.

## Shiny App Demo Video
Watch my Shiny App Demo video on YouTube: https://youtu.be/k8GJQmlML18 

## Result
- Final Mark 75/100

## Room for improvement
- **Feature Standardisation:** Normalising numerical features could improve the performance of models like Logistic Regression, by ensuring all independent variables are on the same scale.
- **Model Tuning:** Applying grid-search or cross-validation for hyperparameter optimisation could improve the models' performance further.
