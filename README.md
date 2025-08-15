# 📊 Data-Driven Inventory & Sales Trend Analysis for Tiwari Vastralaya

> **BDM Project** – IIT Madras BS Degree Program  
> Author: Guddu Mishra | Roll No: *[22f3001315]*

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Analysis-yellow?logo=pandas)
![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Charts-orange?logo=plotly)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Overview
This project focuses on **improving inventory planning and sales management** for *Tiwari Vastralaya*, a local ethnic clothing store in Kushinagar, Uttar Pradesh.  
Using **12 weeks of primary sales data**, we performed **trend analysis, ABC classification, coefficient of variation (CV) analysis, and forecasting** to identify **stock priorities, sales cycles, and demand patterns**.

---

## 🏪 Organization Background
- **Business Type:** Family-run clothing store
- **Products:** Sarees, Suits, Lehengas, Bedsheets
- **Challenges:**
  - 📦 Limited storage space
  - 📉 Irregular non-festive sales
  - 🖥️ No digital forecasting tools
- **Objective:** Use data analysis to make **better stocking & sales decisions**.

---

## 🎯 Project Goals
- Identify **top-performing products** using **ABC classification**.
- Detect **sales fluctuations** with **trend analysis**.
- Measure **demand stability** using **CV analysis**.
- Forecast **short-term demand** using **Random Forest**.

---

## 📂 Data Collection & Methodology
**Data:**  
- **Type:** Primary sales data (Feb–Apr 2025)  
- **Items:** 60+ products across 4 categories  
- **Source:** Manual sales registers → Excel sheets

**Tools & Techniques:**
- 🐍 Python (Pandas, NumPy, Scikit-learn, Plotly)
- 📈 Trend Analysis (Category-wise & Total Sales)
- 🎯 ABC Classification
- 📊 Coefficient of Variation
- 🤖 Random Forest Regressor for Forecasting

---

## 📊 Key Visuals

### **1️⃣ Weekly Sales Trend by Category**
![Trend Chart](assets/trend_chart.png)

### **2️⃣ ABC Classification Curve**
![ABC Curve](assets/abc_curve.png)

### **3️⃣ Forecasting for Key Products**
![Forecast](assets/forecast_plot.png)

---

## 🔍 Key Findings
- **A-Category items (55%)**: Sarees & Suits drive majority sales.
- Sales show a **2-week cyclic pattern**, with peaks likely tied to paydays/events.
- **CV analysis** highlights stable vs. highly variable products.
- Forecasting is **more accurate for Suits (R² = 0.94)** than Sarees (R² = 0.76).

---

## 💡 Recommendations
**Short-Term:**
- Stock **A-category** items in prime store space.
- Prepare for **high-sales weeks** using trend data.
- Use **forecasts** to guide restocking.

**Long-Term:**
- Store excess inventory in **unused front room**.
- Adopt **Excel or simple inventory software**.
- Partner with **local delivery platforms** to expand reach.

---

## 🚀 How to Run the Code
```bash
# Clone the repository
git clone https://github.com/gkmfrombs/BDM-capstone-project-by-Guddu-Mishra.git

# Navigate to project folder
cd tiwari-vastralaya-analysis

# Install dependencies
pip install -r requirements.txt

# Run analysis
python analysis.py
```

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 🙌 Acknowledgments
Special thanks to **Tiwari Vastralaya** for providing access to primary sales data,  
and to **IIT Madras** for guiding the analytical approach through the **BDM course**.

---
