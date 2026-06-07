# Telco Customer Churn Analysis & Prediction

This project analyzes customer churn behavior using the Telco Customer Churn dataset. The goal is to explore customer patterns, identify key churn factors, and build machine learning models to predict whether a customer is likely to churn.

## Project Type

* Data Analysis Project
* Machine Learning Project
* Customer Churn Prediction
* Academic / Portfolio Project

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* scikit-learn
* XGBoost

## Project Workflow

The notebook covers the following steps:

1. Loading the Telco Customer Churn dataset
2. Data cleaning and preprocessing
3. Handling missing values
4. Encoding categorical variables
5. Exploratory Data Analysis
6. Feature analysis
7. Model training and evaluation
8. Comparing machine learning models
9. Summarizing churn insights and business recommendations

## Machine Learning Models Used

The project compares multiple models, including:

* Logistic Regression
* Random Forest
* XGBoost

## Key Insights

The analysis focuses on churn-related patterns such as:

* Contract type and its impact on churn
* Tenure and customer loyalty
* Monthly charges and churn behavior
* Service-related factors affecting customer retention

## Best Model

Logistic Regression achieved strong overall performance and was selected as a suitable model due to its balance between accuracy, interpretability, and simplicity.

## Repository Contents

```text
telco-churn-prediction/
│
├── telco_churn_analysis_prediction.ipynb
├── README.md
└── requirements.txt
```

## Dataset Setup

The dataset is **not included** in this repository.

Before running the notebook, download the Telco Customer Churn dataset from Kaggle and place the CSV file in the same folder as the notebook.

The file should be named exactly:

```text
WA_Fn-UseC_-Telco-Customer-Churn.csv
```

Expected structure:

```text
telco-churn-prediction/
│
├── telco_churn_analysis_prediction.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── README.md
└── requirements.txt
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/m01yyad/telco-churn-prediction.git
```

2. Navigate to the project folder:

```bash
cd telco-churn-prediction
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Download the dataset from Kaggle and place it in the project folder with this exact name:

```text
WA_Fn-UseC_-Telco-Customer-Churn.csv
```

5. Open the notebook:

```bash
jupyter notebook telco_churn_analysis_prediction.ipynb
```

## Note

This project was developed for learning and portfolio purposes. The results are based on exploratory data analysis and machine learning experiments on the Telco Customer Churn dataset.
