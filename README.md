# House Price Prediction

## Problem
The goal of this project is to predict house prices using features like size, quality, and location.

---

## Dataset
- Source: Kaggle (House Prices dataset)
- Around 1460 houses
- Includes both numerical and categorical features

---

## What I Did

- Selected a few important features like:
  - Overall quality
  - Living area
  - Garage area
  - Basement area
  - Number of bathrooms and bedrooms
  - Neighborhood (location)

- Converted categorical data (like Neighborhood) into numerical form using one-hot encoding

---

## Models Used

### Linear Regression
- Used as a baseline model
- Gave better performance in this case

### Decision Tree
- Tried to capture non-linear patterns
- Tuned using `max_depth`

---

## Results

- Linear Regression MAE: ~21,900  
- Decision Tree MAE: ~24,150  

Linear Regression performed better on this dataset.

---

## What I Learned

- Choosing the right features matters a lot  
- Adding more features doesn’t always help  
- Decision Trees can overfit if not controlled  
- Simpler models can sometimes perform better than complex ones  

---

## Possible Improvements

- Try more features  
- Use models like Random Forest  
- Do better feature engineering  

---

## Tools Used

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Jupyter Notebook
