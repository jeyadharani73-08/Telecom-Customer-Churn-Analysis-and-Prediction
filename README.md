# Telecom-Customer-Churn-Analysis-and-Prediction
 This project focuses on Exploratory Data Analysis (EDA), data visualization, feature selection, and classification models to identify customer churn patterns and understand the factors influencing customer retention.
 # Telecom Customer Churn Analysis and Prediction

## Project Overview

This project focuses on analyzing customer churn in the telecommunications industry using Exploratory Data Analysis (EDA) and Machine Learning techniques.

The main objective is to understand customer behaviour, identify patterns associated with customer churn, and build classification models to predict whether a customer is likely to leave the service.

## Dataset Information

- **Dataset:** Customer Churn
- **Records:** 3,150
- **Features:** 13 input features
- **Target Variable:** Churn

The dataset contains customer information such as call failure, complaints, subscription length, usage frequency, SMS frequency, tariff plan, age, and customer value.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

### 1. Data Loading and Inspection
- Imported the customer churn dataset.
- Examined dataset structure, columns, and data types.
- Checked missing values and duplicate records.

### 2. Data Cleaning and Preprocessing
- Converted columns into appropriate numerical data types.
- Handled missing values where required.
- Applied the Interquartile Range (IQR) method for outlier treatment.
- Prepared numerical and categorical features.

### 3. Exploratory Data Analysis
Performed visualizations to understand customer behaviour:

- Churn vs Non-Churn Customer Distribution
- Customer Age Distribution
- Churn Rate by Complaints
- Churn Rate by Tariff Plan
- Correlation Heatmap

### 4. Feature Selection
Used `SelectKBest` with the ANOVA F-test (`f_classif`) to identify relevant features.

### 5. Model Building

The following classification algorithms were explored:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### 6. Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score

## Project Structure

```text
Customer-Churn-Analysis/
│
├── Customer_Churn_EDA.ipynb
├── Customer Churn.xls
└── README.md
```

## Installation

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl xlrd jupyter
```

## How to Run

1. Clone this repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

2. Open the project folder.

3. Make sure the dataset file is in the same folder as the notebook.

4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `Customer_Churn_EDA.ipynb` and run the cells.

## Project Objective

The project aims to understand the factors associated with customer churn and explore how machine-learning classification techniques can help identify customers who may leave a telecommunications service.

## Future Improvements

- Improve model performance through hyperparameter tuning.
- Address class imbalance.
- Compare additional classification algorithms.
- Develop a simple interface for customer churn prediction.

## Author

Jeyadharani P


