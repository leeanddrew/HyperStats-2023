# 🚀 STLE Prediction in Hypersonic Vehicles

This project explores the use of supervised learning and deep learning models to predict **Shock-induced Turbulent Laminar Equilibrium (STLE)** locations in hypersonic vehicles using sparse pressure sensor data.

📁 All code is implemented in Jupyter notebooks and based on experimental aerodynamic data.

---

## 🧠 Problem Statement

Given time-series pressure sensor readings from hypersonic wind tunnel experiments, the goal is to accurately predict the location of STLE – a key aerodynamic event that influences vehicle stability at high speeds.

---

## 🔍 Approach

- Built baseline and advanced **supervised learning models**:
  - Linear Regression
  - Random Forest
  - Support Vector Machines (SVM)
- Engineered time-series features to denoise pressure signals and improve model accuracy
- Trained a **deep neural network** using only 7 of 37 total runs and evaluated on >900K test observations

---

## 📈 Key Results

- 📉 **Reduced Mean Squared Error by 77%**
- 📈 **Improved R² from 0.79 to 0.89**
- 🧪 DNN generalized well to unseen test conditions, despite limited training set size

