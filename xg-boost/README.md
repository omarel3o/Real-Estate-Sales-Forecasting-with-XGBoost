# 🏡 Real Estate Sales Forecasting with XGBoost

This project predicts monthly unit sales and unit pricing for a real estate product using historical sales data and machine learning. The model is built using XGBoost and enhanced with smart feature engineering to track trends, momentum, and seasonality.

---

## ✨ Project Summary

Using real-world structured data from 2024, this notebook forecasts sales and price performance for January 2025, and compares predictions against actual results through detailed visualizations. It helps identify how pricing and engagement metrics affect future sales volumes.

---

## 📊 Detailed Project Description

The notebook handles the full machine learning pipeline:

- **Data Upload**: Upload real estate sales data for 2024 and actual results for January 2025.
- **Data Processing**: Cleans, transforms, and engineers features like previous sales and sales momentum.
- **Model Training**: Trains an XGBoost regression model with optimized parameters to reduce error and boost prediction accuracy.
- **Prediction**: Estimates the number of units sold and their price in January 2025 based on inflation and demand assumptions.
- **Validation**: Compares model predictions against actual January 2025 sales using structured tables.
- **Visualization**:
  - Price evolution over 2024
  - Relationship between price and sales
  - Predicted vs actual price comparison
  - Predicted vs actual units sold comparison

The project is designed for freelancers, analysts, and real estate professionals who want measurable, model-driven insights into pricing and sales behavior.

---

## 🚀 How to Run

1. Open the notebook in **Google Colab**.
2. Upload the original sales file for 2024 when prompted.
3. Upload the actual January 2025 results file when prompted.
4. Run all cells to see predictions, evaluation metrics, and rich comparison plots.

---

## 📁 Input File Formats

**2024 Sales File**  
CSV containing monthly unit sales with fields:  
`Date`, `Product Name`, `Units Sold`, `Unit Price (EGP)`, `Discount (%)`, `Website Visits`, `Price after discount`

**Actual January 2025 File**  
Single-row CSV with same structure, for January 2025 only.

---

## 🧪 Evaluation Metrics

- R² Score
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)

---

## 🎨 Tech Stack

- Python 3.x
- Pandas, NumPy
- XGBoost
- scikit-learn
- Seaborn, Matplotlib

---

## 📬 Contact

Project built by **Omar**  
Data-driven, AI-powered solutions for real-world forecasting and decision making.
