# Applying Logistic Regression and SMOTE for Analyzing and Predicting Customer Churn in Advertising with Imbalanced Data

This project explores the issue of customer churn in the advertising industry, particularly focusing on the challenges of dealing with imbalanced data. The analysis includes Logistic Regression as the classification method and SMOTE (Synthetic Minority Over-sampling Technique) to handle the class imbalance. The dataset used in this project was sourced from [Kaggle](https://www.kaggle.com/datasets/hassanamin/customer-churn/data), and Python was utilised for data manipulation, visualization, and modeling.

## Prerequisites

Ensure you have Python installed (preferably version 3.8 or later).

## Setup Instructions

### 1. Create a virtual environment:

```bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
```

### 2. Install the required packages:

```bash
pip install -r requirements.txt
```

### 3. Run the Jupyter Notebook:

```bash
jupyter notebook
```

## Files Included

* `customer_churn_analysis.ipynb`: The Jupyter Notebook containing the analysis.
* `requirements.txt`: A file listing the required packages.
* `customer_churn.csv`: A sample of the dataset used in the analysis.
* `README.md`: This file with instructions.
* `LICENSE.md`: Contains the project licensing information. 

The dataset used for this project comes from Kaggle, and it contains customer information of a marketing agency that is critical for churn prediction. Although metadata is not provided, the dataset includes features related to customer behavior and business interactions.

## Running the Analysis

1. Open `customer_churn_analysis.ipynb` in Jupyter Notebook.
2. Follow the steps in the notebook to perform the analysis, which involves data pre-processing, dealing with imbalanced data using SMOTE, training the Logistic Regression model, and evaluating its performance.
3. Review the results and insights, especially in terms of how the model handles the class imbalance and the effectiveness of SMOTE.

## Libraries Used

The following libraries are used in this project:

* `pandas`, `numpy` – for data manipulation and analysis.
* `matplotlib`, `seaborn` – for data visualization.
* `hashlib` – for anonymising data.
* `scipy.stats` – for statistical tests like t-tests and chi-square tests.
* `imblearn` – specifically SMOTE for handling imbalanced datasets.
* `sklearn` – for train-test splitting, scaling data, Logistic Regression and performance evaluation.