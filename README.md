# 🏠 House Price Prediction Using Machine Learning

## 📌 Project Overview
This project focuses on predicting house sale prices using Machine Learning techniques. It uses the House Prices: Advanced Regression Techniques dataset from Kaggle.

The goal is to analyze housing features, preprocess the data, train regression models, and generate accurate house price predictions.

## 🎯 Objectives
- Perform Exploratory Data Analysis (EDA).
- Handle missing values and outliers.
- Perform feature engineering.
- Apply categorical encoding.
- Train and compare multiple Machine Learning models.
- Generate house price predictions.

## 📊 Dataset
**Source:** Kaggle – House Prices: Advanced Regression Techniques

- Training dataset: 1,460 records
- Testing dataset: 1,459 records
- Target variable: SalePrice

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Kaggle Notebook

## 🤖 Machine Learning Models
1. Random Forest Regressor
2. Gradient Boosting Regressor
3. Extra Trees Regressor
4. Ensemble Model

## 📈 Model Evaluation

Models were evaluated using Root Mean Squared Error (RMSE).

| Model | Validation RMSE |
|---|---:|
| Random Forest | 29595.31 |
| Gradient Boosting | 28705.53 |
| Extra Trees | 28099.37 |
| Ensemble | 27595.16 |

The Ensemble Model achieved the lowest validation RMSE among the tested models.

# 📁 Project Structure

- `house-price-prediction-professional.ipynb` – Complete machine learning implementation.
- `README.md` – Project documentation.
- `.gitignore` – Git ignored files configuration.

- - `submission.csv` – Final house price predictions for 1,459 test records.
 
## Installation and Usage

1. Clone this repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Run all cells sequentially.
5. The final predictions will be saved as submission.csv.

## Required Libraries
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## 🚀 Results
The trained ensemble model generates predictions for 1,459 test records and saves them in a CSV submission file.

## 👩‍💻 Author
Pragati Jain

GitHub: [jainpragatii](https://github.com/jainpragatii)
