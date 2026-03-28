# House-Price-Prediction-using-Machine-Learning

#### Project Overview

This project focuses on building a Machine Learning model to predict house prices based on various property features such as size, location, condition, and construction details.

The goal is to help a real estate company (HomeVista Properties) automate pricing decisions using historical data and predictive analytics.

#### 🎯 Problem Statement

HomeVista Properties deals with thousands of property sales across multiple cities.
Manual price estimation is time-consuming and inconsistent.

👉 Objective:
Develop a Linear Regression model to automatically predict house prices using structured housing data.

📊 Dataset Description

Each row represents a residential property with features like:

| Feature      | Description              |
| ------------ | ------------------------ |
| Id           | Unique house ID          |
| MSSubClass   | Type of dwelling         |
| MSZoning     | Zoning classification    |
| LotArea      | Lot size (sq ft)         |
| LotConfig    | Lot configuration        |
| BldgType     | Type of building         |
| OverallCond  | Overall condition (1–10) |
| YearBuilt    | Construction year        |
| YearRemodAdd | Remodel year             |
| Exterior1st  | Exterior material        |
| BsmtFinSF2   | Basement finished area   |
| TotalBsmtSF  | Total basement area      |
| SalePrice 🎯 | Target variable          |

#### 🧹 Data Preprocessing

✔ Handled missing values
✔ Converted categorical variables using encoding
✔ Cleaned inconsistent data formats
✔ Removed irrelevant columns (e.g., Id)
✔ Feature scaling where required

#### ⚙️ Model Building
Algorithm Used: Linear Regression
Train-Test Split: 80/20
Feature Selection applied
Model trained on cleaned dataset

#### 📈 Model Evaluation

The model was evaluated using:

R² Score (Coefficient of Determination)
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)

📌 These metrics help measure prediction accuracy and error distribution.

🛠 Tech Stack
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
