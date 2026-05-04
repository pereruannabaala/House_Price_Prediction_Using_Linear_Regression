# House Price Prediction using Linear Regression

##  Project Overview
This project focuses on predicting house prices using a Linear Regression model.  
The objective was to improve an existing model by adding more relevant features and evaluating the impact on prediction accuracy.

---

## Dataset
- Source: Kaggle House Prices Dataset (`train.csv`)
- The dataset contains 80+ features describing different aspects of residential homes
- Target variable: `SalePrice`

---

## Initial Model

### Features Used:
- GrLivArea (Above ground living area)
- OverallQual (Overall quality of the house)
- YearBuilt (Year the house was built)

### Performance:
- RMSE: **43,186.90**

---

## Improved Model

### Additional Features Added:
- TotalBsmtSF (Total basement area)
- GarageCars (Garage capacity)
- GarageArea (Garage size)
- FullBath (Number of full bathrooms)
- TotRmsAbvGrd (Total rooms above ground)

---

## Feature Selection Justification
The additional features were selected because they have a strong influence on house pricing:

- Larger **basement space** increases usable area  
- **Garage capacity and size** improve property value  
- More **rooms and bathrooms** increase livability and demand  

These features help the model better understand real-world housing value drivers.

---

## Model Performance Comparison

| Model        | RMSE       |
|-------------|-----------|
| Initial     | 43,186.90 |
| Improved    | 39,661.16 |

---

## Improvement Analysis

- RMSE Reduction: **3,525.74**
- Percentage Improvement: **~8.16%**

The improved model makes predictions that are, on average, closer to the actual house prices by over $3,500.

---

## Conclusion
By incorporating additional relevant features, the model was able to capture more meaningful relationships in the data.  

This led to improved prediction accuracy, demonstrating that **feature selection plays a critical role in machine learning performance**.

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## Project Structure
- `House_Price_Prediction.ipynb` → Notebook with full implementation
  
---

## Author
Pereruan Nabalala
