## Walmart Store Sales Forecasting (Elevvo Internship - Task 7)

## 📌 Project Overview
This project predicts weekly sales for Walmart stores using machine learning.  
The dataset includes information about sales, store characteristics, and external factors such as holidays and markdowns.  
The goal is to build a predictive model to help Walmart plan inventory, staffing, and marketing strategies more effectively.

---

## 📂 Dataset
The project uses **four datasets**:
1. **train.csv** – Historical sales data for stores (Store, Dept, Date, Weekly_Sales, IsHoliday).  
2. **features.csv** – Additional store information (Temperature, Fuel Price, CPI, Unemployment, MarkDowns, etc.).  
3. **stores.csv** – Metadata about stores (Store Type, Size).  
4. **test.csv** – Test dataset for predictions.  

---

## ⚙️ Approach
1. **Data Loading & Merging**  
   - Combined sales, features, and stores datasets.  
   - Ensured correct datetime formatting for the `Date` column.  

2. **Preprocessing**  
   - Handled missing values.  
   - Encoded categorical variables (`Type`, `IsHoliday`).  
   - Extracted features like Year, Month, Week from `Date`.  

3. **Exploratory Data Analysis (EDA)**  
   - Checked trends in sales, seasonality, and impact of holidays.  
   - Visualized sales across stores and departments.  

4. **Modeling**  
   - Applied **Random Forest Regressor** to predict `Weekly_Sales`.  
   - Evaluated performance using **R² Score** and **RMSE**.  

5. **Prediction**  
   - Generated weekly sales predictions on the test dataset.  

---

## 🛠️ Tech Stack
- **Python**  
- **Pandas, NumPy** (data manipulation)  
- **Matplotlib, Seaborn** (visualization)  
- **Scikit-learn** (machine learning models & evaluation)  

---

## 📊 Results
- The model provides sales forecasts with reasonable accuracy.  
- Feature importance analysis shows which factors (e.g., holidays, CPI, unemployment) impact sales the most.  

