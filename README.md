# 📊 Customer_Churn_Analysis

**Author:** Laxmi  
**Project Type:** Data Analytics | Customer Churn | LTV Analysis  
**Tools Used:** Python (Pandas, NumPy, Matplotlib, Seaborn), Jupyter Notebook  
**Dataset Source:** IBM Sample Data Sets (Kaggle)

---

## 📌 Project Overview

Customer churn is a major challenge in the telecom industry. This project analyzes customer behavior to identify key drivers of churn and Customer Lifetime Value (LTV), helping businesses design focused customer retention strategies.

---

## 📂 Dataset Description

- **Source:** IBM Sample Dataset – Telco Customer Churn  
- **Rows:** 7,043 customers  
- **Columns:** 21 features  
- **Target Variable:** `Churn`  
- **Description:** Each row represents a customer, and each column contains customer attributes described in the metadata.

🔗 Dataset Link:  
https://www.kaggle.com/blastchar/telco-customer-churn

---

## 📁 Repository Structure

- `Customer_Churn_Analysis.ipynb` – Data cleaning, EDA, segmentation, and analysis 
- `Visualization.slides.html` – Final presentation slides (download to view)

---

## 🔍 Key Insights

- The **top 20% of churned customers** have an average **LTV of $4,750**, while the remaining **80% average $750**.  
- The **top 20% account for ~60% of total lost revenue**, indicating high-value churn risk.  
- **80% of low-LTV churned customers left within 10 months**, suggesting early-stage churn behavior.  
- Only **5% of low-LTV churned customers used internet services**, while **100% of extremely high-LTV customers used internet services**.  
- **81% of customers with tenure over 50 months** tend to use **multiple lines**.  
- **89% of churned customers were on monthly contracts**, compared to **42% among retained customers**.  
- **Internet service usage** is the strongest driver of high LTV, followed by **yearly contracts**.  
- Among internet service features, **online backup** has the highest impact on increasing LTV.

---

## 📉 Insights on Current Customers

- In the **top 80% of current customers**, all internet service types are used almost equally (~40%).  
- Outside this group, **streaming TV and streaming movies** are the most used services.  
- High-LTV current customers are **10% more likely** to use **multiple lines and internet services** than average customers.

---

## ⚠️ Limitations

- Dataset does not capture **changes in customer preferences over time**.  
- External factors such as **competitor pricing or economic conditions** are not included.  
- Lack of churn timestamp limits time-based analysis.

---

## 📌 Conclusion

The analysis shows that **retaining high-LTV customers**, especially those using internet services and long-term contracts, can significantly reduce revenue loss. Targeted retention strategies for these segments offer higher business impact than volume-based churn reduction.

---

## 🚀 Future Improvements

- Add churn prediction using machine learning models  
- Include time-series behavior analysis  
- Integrate pricing and competitor data

---

⭐ If you find this project useful, feel free to star the repository!



