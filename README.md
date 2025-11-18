# FUTURE_ML_01
📊 Task 1 – AI-Powered Sales Forecasting Dashboard (Future Interns – ML Track)

This repository contains my submission for **Task 1** of the **Machine Learning Internship at Future Interns**.

The goal of this task is to build a **Sales Forecasting Dashboard** using real-world retail data, apply machine learning forecasting models, and present insights through graphs.

---
Objective

To analyze retail sales data and forecast future sales using historical daily sales.  
The results help in understanding demand patterns, trends, seasonal effects, and business insights.

---

## 📁 **Dataset Used**
- **Sample - Superstore.csv**
- Contains order-level retail sales data  
- Columns used:  
  - `Order Date`  
  - `Sales`  

The dataset was cleaned and converted to **daily aggregated sales** for forecasting.

---

## 🛠️ **Technologies & Tools Used**
- **Python**
- **Pandas** – Data cleaning & grouping  
- **Prophet** – Time series forecasting  
- **Matplotlib** – Visualization  
- **Google Colab** – Coding environment  

---

## 🔧 **Steps I Followed**

1. Loaded the Superstore dataset  
2. Cleaned & extracted required columns  
3. Converted `Order Date` to datetime  
4. Grouped the dataset to get **daily total sales**  
5. Prepared the data for Prophet (`ds`, `y` format)  
6. Trained the Prophet model  
7. Predicted the **next 30 days of future sales**  
8. Generated visualizations:
   - Forecast plot  
   - Trend plot  
   - Weekly/Yearly seasonality analysis  

---

## 📈 **Output Visuals**

### 🔹 Sales Forecast Graph
Predicts the sales for the next 30 days based on historical data.

### 🔹 Trend & Seasonality Graphs
Shows:
- Long-term upward/downward trend  
- Weekly repeating patterns  
- Yearly seasonality  

These insights are commonly used in business decisions like inventory planning and marketing.

---

## 📦 **Files Included in This Repository**
| File Name | Description |
|----------|-------------|
| `task1_daily_forecasting.ipynb` | Main Google Colab notebook with complete forecasting code |
| `Sample - Superstore.csv` | Dataset used |
| `forecast.png` | Forecast graph (main dashboard output) |
| `components.png` | Trend and seasonality components |
| `README.md` | Documentation |

---

## 🏆 **Internship Details**
- Organization: **Future Interns**  
- Track: **Machine Learning (ML)**  
- Task: **Task 1 – Sales Forecasting Dashboard**  
- Status: ✔ Completed  

---

## 🌐 **Connect With Me**
Feel free to explore my notebook and visual outputs above.  
More tasks from this internship will be uploaded soon.

