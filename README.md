# ANN Regression Model for Power Plant Energy Prediction

## 📌 Project Overview
This project builds an **Artificial Neural Network (ANN) Regression model** to predict the **electrical energy output (EP)** of a **Combined Cycle Power Plant (CCPP)** based on environmental and operational parameters.  

The dataset contains **9,568 data points** collected over **6 years** (2006–2011), from a power plant in Turkey.

---

## 🎯 Objective
To develop a regression model using an ANN that predicts **net electrical energy output** given the following features:
- Temperature (T) in °C  
- Ambient Pressure (AP) in millibar  
- Relative Humidity (RH) in %  
- Exhaust Vacuum (V) in cm Hg  

---


---

## 📊 Dataset
- **Source**: UCI Machine Learning Repository  
- **Dataset Name**: Combined Cycle Power Plant (CCPP)  
- **Target Variable**: Net Electrical Energy Output (EP) in MW  

👉 [Dataset Link](https://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant)

---

## ⚙️ Methodology
1. **Data Preprocessing**  
   - Handle missing values (if any)  
   - Feature scaling (Normalization/Standardization)  
   - Train-Test split  

2. **Exploratory Data Analysis (EDA)**  
   - Correlation analysis  
   - Feature importance  
   - Visualization of input vs output  

3. **Model Development**  
   - Build an Artificial Neural Network (ANN) Regression model using TensorFlow/Keras  
   - Hyperparameter tuning (layers, neurons, activation functions, optimizer)  

4. **Evaluation**  
   - Metrics: **MAE, MSE, RMSE, R² Score**  
   - Comparison with baseline models (Linear Regression, Decision Tree, Random Forest)  

---

## 🛠️ Tech Stack
- Python 3.x  
- NumPy, Pandas, Matplotlib, Seaborn  
- Scikit-learn  
- TensorFlow / Keras  

---

