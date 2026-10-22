# 📱 Mobile Price Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

An end-to-end Machine Learning project designed to predict mobile phone prices based on hardware specifications and technical features using regression modeling.

---

## 📌 Project Overview

Understanding the relationship between hardware components and phone pricing is essential for market analysis and pricing strategy. This project explores feature correlation with mobile prices and builds a linear regression model to accurately predict pricing based on technical specifications.

## 🎯 Objective

- Analyze key technical specifications that influence mobile pricing.
- Conduct exploratory data analysis (EDA) and feature correlation evaluation.
- Train and evaluate a **Linear Regression** model to accurately estimate phone prices.

---

## 📊 Dataset Overview

The dataset contains **161 records** across **14 features** with zero missing values.

| Feature Category | Features Included |
| :--- | :--- |
| **Performance** | RAM, Internal Memory, CPU Cores, CPU Frequency |
| **Display & Design**| Resolution, PPI (Pixels Per Inch), Weight, Thickness |
| **Camera & Battery**| Rear Camera, Front Camera, Battery Capacity |
| **Target Variable** | Sale Price |

---

## 🔍 Exploratory Data Analysis & Key Insights

Through statistical summarization and correlation analysis, key patterns were identified:

- **Strong Positive Predictors:** `RAM`, `PPI`, `Internal Memory`, `Rear Camera`, `CPU Frequency`, and `CPU Cores` show strong positive correlations with `Price`.
- **Negative Predictor:** `Thickness` exhibits an inverse correlation with price (thinner phones tend to command higher prices).

---

## 🤖 Machine Learning Implementation

A **Linear Regression** model was trained to predict price points continuously based on hardware metrics. Model performance was measured using standard evaluation metrics:

- **R² Score** (Coefficient of Determination)
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**

---

## 🛠️ Technologies Used

- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn

---

## 📁 Repository Structure

```text
Mobile-Price-Prediction/
├── mobile_price.csv              # Dataset
├── Mobile_Price_Prediction.ipynb  # Exploratory Data Analysis & Model Training Notebook
└── README.md                     # Project Documentation
