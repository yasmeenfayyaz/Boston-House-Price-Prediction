# Boston House Price Prediction using Linear Regression

This repository contains a Machine Learning project focused on predicting house prices in Boston using **Linear Regression**. This project was developed as part of my Machine Learning workflow practice, focusing on exploratory data analysis, feature selection, and model evaluation.

---

## 📌 Project Overview
The objective of this project is to build a regression model that can estimate the median value of owner-occupied homes (`MEDV`) based on key socio-economic and structural features of the neighborhood.

### Selected Features:
* **RM**: Average number of rooms per dwelling.
* **LSTAT**: Percentage of lower status of the population.
* **PTRATIO**: Pupil-teacher ratio by town.
* **TAX**: Full-value property-tax rate per $10,000.

---

## 📊 Dataset
The dataset used in this project is the classic **Boston House Prices dataset** (`boston.csv`). It contains various attributes of houses in Boston suburbs.
* **Target Variable**: `MEDV` (Median value of owner-occupied homes in $1000's)

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Environment:** Google Colab / Jupyter Notebook
* **Libraries:** 
  * `pandas` & `numpy` (Data Manipulation)
  * `matplotlib` & `seaborn` (Data Visualization)
  * `scikit-learn` (Model Training & Evaluation)

---

## 📈 Model Performance
The data was split into **80% Training** and **20% Testing** sets. A Linear Regression model was trained and evaluated using the following metrics:

| Metric | Value |
| --- | --- |
| **Root Mean Squared Error (RMSE)** | `5.2255` |
| **R² Score (Coefficient of Determination)** | `0.6277` (62.77%) |

---

## 📉 Visualizations
Here is the scatter plot showing the **Actual vs Predicted Prices**. The closer the points are to the red line, the more accurate the model's predictions are.

https://colab.research.google.com/drive/1PRmC0sI_Uhy5ELI7azhLBaW0HoeAlDqN#scrollTo=iDkGLHVRE2sz&fullscreenOutput=true

---

## 🚶‍♂️ How to Run the Project
1. Clone this repository:
   ```bash
   https://github.com/yasmeenfayyaz/Boston-House-Price-Prediction
   
