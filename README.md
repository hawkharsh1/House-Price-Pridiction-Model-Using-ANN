# 🏠 House Price Prediction Model Using ANN (Deep Learning)

A deep learning-based regression model built using **Artificial Neural Networks (ANN)** in **PyTorch** to predict house prices from structured data. This project demonstrates the application of machine learning and deep learning techniques for solving real-world problems in the housing domain.

---

## 🔍 Problem Statement

Predicting house prices accurately is a classic machine learning challenge. This model aims to:

- Learn the relationship between input features (like number of rooms, location, area, etc.) and the target price.
- Generalize well on unseen data using deep learning techniques.
- Serve as a foundation for more complex real-estate forecasting systems.


## 🎯 Objectives

- Build an accurate regression model using PyTorch ANN.
- Normalize and preprocess data for deep learning models.
- Evaluate the model using **RMSE** and visualize learning progress.
- Provide a clean, readable, and reproducible Jupyter Notebook.

## 🚀 Project Highlights

- Built an end-to-end ANN model using PyTorch to predict house prices.
- Preprocessed structured data using **NumPy**, **Pandas**, and **Scikit-learn**.
- Trained and evaluated using **Root Mean Squared Error (RMSE)**.
- Visualized training loss with **Matplotlib**.
- Scalable to any similar structured dataset.

---

## 🛠️ Tech Stack and Libraries

| Component        | Tool / Library    |
|------------------|-------------------|
| Programming Lang | Python 3.10+       |
| Framework        | PyTorch            |
| Data Handling    | Pandas, NumPy      |
| Modeling Tools   | Scikit-learn       |
| Visualization    | Matplotlib         |
| Environment      | Jupyter Notebook   |

## 🔁 Data Preprocessing Pipeline

1. **Load data** using Pandas
2. **Handle missing values** (drop/fill as needed)
3. **Encode categorical variables** using `LabelEncoder` or `OneHotEncoder`
4. **Feature scaling** using `StandardScaler`
5. **Train-test split** using `train_test_split`
6. **Convert data to PyTorch tensors**

## 📐 Neural Network Overview

The ANN model consists of:
- Input layer with N features (based on dataset)
- 2 hidden layers with 64 and 32 neurons respectively
- ReLU activation functions
- Output layer with 1 neuron for price prediction





