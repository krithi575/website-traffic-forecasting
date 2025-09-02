# Website Traffic Forecasting 📈  

This project demonstrates **time series analysis and forecasting** on website traffic data.  
We use **Python, statsmodels, and ARIMA/SARIMAX models** to analyze traffic patterns and predict future visits for **The Clever Programmer** website.  

---

## 📂 Project Structure
- `website traffic forecasting.ipynb` → Main notebook with analysis and forecasting  
- `Thecleverprogrammer.csv` → Dataset containing daily traffic (date & views)  

---

## 📊 Steps in the Project
1. **Data Loading & Cleaning**  
   - Load dataset (`Thecleverprogrammer.csv`)  
   - Convert `Date` column to datetime format  

2. **Exploratory Data Analysis (EDA)**  
   - Line plot of daily traffic  
   - Seasonal decomposition to visualize **trend, seasonality, and residuals**  

3. **Time Series Modeling**  
   - Applied **SARIMAX (Seasonal ARIMA)** model with chosen hyperparameters `(p,d,q)`  
   - Fitted model and displayed summary statistics  

4. **Forecasting**  
   - Predicted website traffic for the next 50 days  
   - Compared training data vs. predictions using visualization  

---

## ⚙️ Technologies Used
- Python 3  
- Pandas  
- Matplotlib & Plotly  
- Statsmodels  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/krithi575/website-traffic-forecasting.git
   cd website-traffic-forecasting
