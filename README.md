# Sales Prediction using Python

## Project Overview

This project focuses on predicting product sales based on advertising expenditure using a Linear Regression model. The analysis examines how advertising investments across different media channels influence sales and provides data-driven insights to support marketing decisions.

The project includes data preprocessing, exploratory data analysis, feature selection, model training, evaluation, and sales prediction.

---

## Objective

The main objectives of this project are to:

* Predict future sales based on advertising expenditure.
* Clean and preprocess the dataset.
* Perform exploratory data analysis to understand the data.
* Select relevant features for model training.
* Build and evaluate a Linear Regression model.
* Analyze the impact of different advertising channels on sales.
* Provide actionable business insights for marketing strategies.

---

## Dataset

**Dataset Name:** Advertising Dataset

The dataset contains advertising expenditure across three media channels:

* TV
* Radio
* Newspaper

**Target Variable:**

* Sales

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Project Workflow

1. Import required libraries.
2. Load the dataset.
3. Perform data cleaning and preprocessing.
4. Check for missing values and duplicates.
5. Conduct exploratory data analysis (EDA).
6. Visualize relationships between advertising expenditure and sales.
7. Select features and target variable.
8. Split the dataset into training and testing sets.
9. Train a Linear Regression model.
10. Predict sales using the trained model.
11. Evaluate model performance.
12. Interpret results and derive business insights.

---

## Data Preprocessing

* Loaded the dataset into a Pandas DataFrame.
* Removed unnecessary columns.
* Checked for missing values.
* Checked for duplicate records.
* Prepared the dataset for machine learning.

---

## Exploratory Data Analysis

The following visualizations were created:

* Correlation Heatmap
* Pair Plot
* Sales Distribution
* TV vs Sales Scatter Plot
* Radio vs Sales Scatter Plot
* Newspaper vs Sales Scatter Plot
* Actual vs Predicted Sales Plot

These visualizations helped identify relationships between advertising expenditure and product sales.

---

## Machine Learning Model

**Algorithm Used**

* Linear Regression

The dataset was divided into training and testing sets using an 80:20 ratio. The Linear Regression model was trained using the training dataset and evaluated on the testing dataset.

---

## Model Performance

| Metric                         |  Value |
| ------------------------------ | -----: |
| Mean Absolute Error (MAE)      | 1.4608 |
| Mean Squared Error (MSE)       | 3.1741 |
| Root Mean Squared Error (RMSE) | 1.7816 |
| R² Score                       | 0.8994 |

### Interpretation

* The model explains approximately **89.94%** of the variation in sales.
* The low MAE and RMSE values indicate that the predictions are close to the actual sales values.
* The model demonstrates strong predictive performance for this dataset.

---

## Business Insights

* TV advertising has the strongest positive influence on sales.
* Radio advertising also contributes significantly to sales growth.
* Newspaper advertising has a comparatively lower impact.
* Increasing investment in TV advertising is likely to generate higher sales returns.
* Businesses should prioritize advertising budgets toward TV and Radio channels to maximize marketing effectiveness.

---

## Project Structure

```text
Sales_Prediction/
│
├── dataset/
│   └── Advertising.csv
│
├── notebook/
│   └── Sales_Prediction.ipynb
│
├── images/
│
├── README.md
│
└── requirements.txt
```

---

## Installation

Install the required Python libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## How to Run the Project

1. Clone the repository.
2. Install the required dependencies.
3. Open the Jupyter Notebook.
4. Execute all cells in sequence.
5. Review the visualizations, evaluation metrics, and predictions.

---

## Future Enhancements

* Apply advanced regression algorithms such as Random Forest Regressor or XGBoost.
* Perform hyperparameter tuning to improve model performance.
* Develop an interactive dashboard using Streamlit or Power BI.
* Deploy the trained model as a web application for real-time sales prediction.

---

## Conclusion

This project demonstrates the use of Linear Regression to predict sales based on advertising expenditure. Through data preprocessing, exploratory data analysis, and model evaluation, the model achieved an R² score of **0.8994**, indicating strong predictive capability. The findings highlight that TV and Radio advertising are the most influential factors in driving sales, providing valuable insights for optimizing marketing strategies.

---

## Author

**Raghavi Venkatasalamoorthi**

Integrated M.Sc. Data Science

Amrita Vishwa Vidyapeetham
