# House Price Prediction using XGBoost

## Overview

This project implements a supervised machine learning model to predict house prices using the California Housing dataset from Scikit-learn. An **XGBoost Regressor** is trained on housing features, and its performance is evaluated using standard regression metrics.

---

## Dataset

- **Dataset:** California Housing Dataset
- **Source:** `sklearn.datasets.fetch_california_housing()`
- **Samples:** 20,640
- **Features:** 8 numerical features
- **Target:** Median House Value

---

## Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## Project Workflow

- Load California Housing dataset
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Correlation analysis using heatmap
- Train-test split
- Train XGBoost Regressor
- Evaluate model performance
- Visualize actual vs predicted prices

---

## Model Performance

| Dataset | R² Score | Mean Absolute Error |
|----------|----------|---------------------|
| Training | **0.9472** | **0.1889** |
| Testing | **0.8371** | **0.3079** |

---

## Repository Structure

```
house-price-prediction/
│
├── House_Price_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/your-username/house-price-prediction.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook in Google Colab or Jupyter Notebook.

---

## Results

The XGBoost Regressor achieved an **R² score of 0.8371** on the test dataset, demonstrating strong predictive performance for the California Housing dataset.

---

## Future Improvements

- Hyperparameter optimization using GridSearchCV
- Feature importance visualization
- Model serialization using Joblib
- Interactive prediction interface with Streamlit
- Compare performance with Random Forest, Linear Regression, and CatBoost

---

## Author

**Shraddha Upadhye**
