# 🚗 Car Price Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting the selling price of used cars using machine learning techniques.

The model uses various car-related features such as present price, manufacturing year, driven kilometers, fuel type, selling type, transmission, owner information, and car name to estimate the selling price.

The project covers the complete machine learning workflow, including data exploration, preprocessing, feature transformation, model training, prediction, and evaluation.

## 🎯 Objective

The objective of this project is to build and evaluate a regression model that can predict the selling price of a used car based on its available features.

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Jupyter Notebook**

## 📊 Dataset

The project uses a car dataset containing information about used cars and their selling prices.

### Features

* `Car_Name`
* `Year`
* `Present_Price`
* `Driven_kms`
* `Fuel_Type`
* `Selling_type`
* `Transmission`
* `Owner`

### Target Variable

* `Selling_Price`

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Exploration & Cleaning
   ↓
Exploratory Data Analysis
   ↓
Data Visualization
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Feature Scaling & Encoding
   ↓
Linear Regression
   ↓
Price Prediction
   ↓
Model Evaluation
```

## 🤖 Machine Learning Model

### Linear Regression

Linear Regression is used as the regression algorithm to predict the selling price of used cars.

The dataset is divided into training and testing sets. Numerical features are scaled using `StandardScaler`, while categorical features are transformed using `OneHotEncoder`.

A Scikit-learn pipeline combines preprocessing and model training into a single workflow.

## 📈 Model Evaluation

The model is evaluated using:

* **Mean Absolute Error (MAE)**
* **Root Mean Squared Error (RMSE)**
* **R² Score**

These metrics are used to measure the difference between actual and predicted prices and evaluate the performance of the regression model.

## 📊 Visualizations

The notebook contains visualizations for:

* Selling Price Distribution
* Present Price vs Selling Price
* Year vs Selling Price
* Selling Price by Fuel Type
* Selling Price by Transmission Type
* Correlation Heatmap
* Actual vs Predicted Prices

## 📁 Project Structure

```text
CodeAlpha_Car_Price_Prediction/
│
├── Car_Price_Prediction.ipynb
├── car data.csv
├── README.md
│
└── images/
    ├── selling_price_distribution.png
    ├── present_vs_selling_price.png
    ├── year_vs_selling_price.png
    ├── selling_price_by_fuel_type.png
    ├── selling_price_by_transmission.png
    ├── correlation_heatmap.png
    ├── actual_vs_predicted.png
    └── prediction_error_distribution.png
```

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/sagarkapoor03/CodeAlpha_Car_Price_Prediction.git
```

### 2. Open the Project

Open the project folder in **Jupyter Notebook** or **VS Code**.

### 3. Open the Notebook

```text
Car_Price_Prediction.ipynb
```

### 4. Run the Notebook

Make sure `car data.csv` is present in the same project directory and run the notebook cells sequentially.

## 📌 Key Learning Outcomes

Through this project, I practiced:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Data visualization
* Feature scaling
* Categorical feature encoding
* Regression modeling
* Price prediction
* Model performance evaluation
* Prediction error analysis

## 👨‍💻 Author

**Sagar Kapoor**

GitHub: [@sagarkapoor03](https://github.com/sagarkapoor03)

---

## 📌 Internship Task

This project was completed as part of the **CodeAlpha Data Science Internship** under the **Car Price Prediction with Machine Learning** task.
