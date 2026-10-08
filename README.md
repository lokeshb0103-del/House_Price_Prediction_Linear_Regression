# House Price Prediction using Machine Learning

## Project Overview

This project predicts house prices using **Machine Learning and Linear Regression**. The dataset is preprocessed, analyzed, and used to train a regression model that predicts house prices based on numerical property features.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Linear Regression

## Dataset

The dataset contains various house-related features, with `price` as the target variable.

### Dataset Credits

The dataset used in this project was obtained from **Kaggle**.

**Dataset Source:** Kaggle

All credit for the original dataset goes to the respective Kaggle dataset creator. The dataset is used for educational and machine learning purposes.

## Project Workflow

1. Loaded the house price dataset.
2. Checked for missing values and duplicate records.
3. Checked data types and statistical information.
4. Removed invalid records where the house price was zero.
5. Separated the features (`X`) and target variable (`y`).
6. Selected numerical features for model training.
7. Split the dataset into training and testing sets.
8. Trained a Linear Regression model.
9. Predicted house prices using the test data.
10. Evaluated the model using R² Score, MAE, and MSE.
11. Visualized actual vs. predicted prices.

## Model Performance

| Metric   |         Result |
| -------- | -------------: |
| R² Score |         0.6006 |
| MAE      |      160681.99 |
| MSE      | 59413057706.82 |

The Linear Regression model achieved an **R² score of approximately 0.60**, meaning the model explains around 60% of the variation in house prices.

## Project Files

```text
House-Price-Prediction/
│
├── House_Price_Prediction.ipynb
├── data.csv
└── README.md
```

## Conclusion

This project demonstrates an end-to-end Machine Learning workflow, including data preprocessing, exploratory analysis, feature selection, model training, prediction, and evaluation for a regression problem.

## Author

**Lokesh Babu**
