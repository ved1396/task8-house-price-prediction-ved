# Synent Task 8 - House Price Prediction

## Objective
Build a Machine Learning model to predict house prices using housing-related features from a real-world dataset.

---

## Dataset
Dataset used: House Prices Competition Dataset from Kaggle

The dataset contains various house-related features such as:
- Lot Area
- Overall Quality
- Year Built
- Living Area
- Number of Bedrooms
- Bathrooms
- Neighborhood details
- Sale Price

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Workflow

### 1. Data Preprocessing
- Loaded training dataset
- Checked missing values
- Handled null values
- Encoded categorical features using Label Encoding

### 2. Exploratory Data Analysis (EDA)
Performed:
- Sale Price Distribution Analysis
- Correlation Heatmap
- Feature Importance Analysis

### 3. Model Building
Implemented:
- Linear Regression
- Random Forest Regressor

### 4. Model Evaluation
Models were evaluated using:
- RMSE (Root Mean Squared Error)

### 5. Prediction Analysis
- Compared actual vs predicted prices
- Generated prediction results CSV

---

## Visualizations Included
- Sale Price Distribution
- Correlation Heatmap
- Actual vs Predicted Prices
- Feature Importance
- Model Comparison Chart

---

## Key Insights
1. Overall quality significantly impacts house prices.
2. Larger living areas generally lead to higher prices.
3. Random Forest performed better than Linear Regression.
4. Feature importance analysis identified the most influential housing attributes.

---

## Project Files

```text
task8-house-price-prediction/
│
├── data/
├── images/
├── predictions.csv
├── house_price_prediction.ipynb
└── README.md
```

---

## Output
Successfully built a predictive Machine Learning model capable of estimating house prices based on multiple housing features.