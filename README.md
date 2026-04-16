# Data-Science-Capstone
Analyze SapceX data to predict the reuse of first stage

# 🚀 SpaceX Falcon 9 First Stage Landing Prediction

## 📌 Project Overview

This project analyzes SpaceX launch data to predict whether the **Falcon 9 first stage will be successfully reused (landed)**. The goal is to build a machine learning model that can help estimate launch costs and mission outcomes based on historical data.

---

## 🎯 Problem Statement

SpaceX reduces launch costs significantly by reusing the first stage of its rockets. Predicting whether the first stage will land successfully is crucial for:

* Cost estimation
* Mission planning
* Risk analysis

This project aims to build a predictive model using historical launch data.

---

## 📊 Data Sources

The dataset was collected from:

* SpaceX API
* Wikipedia (web scraping)
* Additional processed datasets provided for analysis

Key features include:

* Launch site
* Payload mass
* Orbit type
* Booster version
* Flight number
* Landing outcome (target variable)

---

## 🛠️ Technologies Used

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Plotly & Dash (for interactive dashboard)
* Folium (for geospatial visualization)
* Scikit-learn (machine learning models)
* BeautifulSoup (web scraping)

---

## 🔍 Project Workflow

### 1. Data Collection

* Extracted launch data via API
* Scraped additional data from Wikipedia

### 2. Data Wrangling

* Cleaned missing and inconsistent values
* Converted categorical variables
* Created new features

### 3. Exploratory Data Analysis (EDA)

* Visualized relationships between features and landing success
* Analyzed trends across years and launch sites
* Used charts like bar plots, scatter plots, and maps

### 4. Feature Engineering

* Encoded categorical variables
* Normalized/standardized data
* Selected relevant predictors

### 5. Model Development

Trained multiple models:

* Logistic Regression
* Support Vector Machine (SVM)
* Decision Tree
* K-Nearest Neighbors (KNN)

Used **GridSearchCV** for hyperparameter tuning.

---

## 🤖 Model Evaluation

Models were evaluated using:

* Accuracy score
* Confusion matrix
* Cross-validation

The best-performing model was selected based on test accuracy and generalization.

---

## 📈 Results

* Successfully built a model to predict first stage landing
* Achieved high accuracy on test data
* Identified key factors influencing landing success:

  * Payload mass
  * Orbit type
  * Launch site

---

## 🌍 Interactive Dashboard

A dashboard was built using Dash to:

* Visualize launch trends
* Compare yearly vs recession-period statistics
* Explore vehicle type performance

---

## 🗺️ Geospatial Analysis

Using Folium:

* Mapped launch sites
* Visualized landing outcomes geographically

---

## 🚧 Challenges Faced

* Handling missing and inconsistent data
* Feature selection for better model performance
* Avoiding overfitting during training

---

## ✅ Conclusion

This project demonstrates how data science and machine learning can be applied to real-world aerospace problems. Predicting rocket reusability helps in understanding cost efficiency and operational success in space missions.

---

## 📌 Future Improvements

* Use more advanced models (XGBoost, Random Forest)
* Incorporate real-time data
* Improve dashboard interactivity
* Deploy as a web application

---


## ⭐ Acknowledgements

* IBM Data Science Capstone Project
* SpaceX public data sources

---
