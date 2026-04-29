# Customer Segmentation Using RFM Analysis

## 📊 Project Overview
This project focuses on segmenting customers based on their purchasing behavior using **RFM (Recency, Frequency, Monetary) analysis** and **KMeans clustering**.

The objective is to identify distinct customer groups, such as high-value customers, at-risk users, and low-engagement segments to support data-driven business decisions.

---

## 🧠 Business Problem
Businesses often struggle to understand:
- Which customers generate the most revenue
- Which customers are at risk of churning
- How to target different customer groups effectively

This project addresses these challenges using customer transaction data.

---

## 🔧 Methodology

### 1. Data Cleaning
- Removed missing Customer IDs
- Filtered out return/cancellation transactions (negative quantities)
- Created `TotalPrice` feature

### 2. Feature Engineering (RFM)
- **Recency**: Days since last purchase
- **Frequency**: Number of transactions
- **Monetary**: Total spending

### 3. Data Transformation
- Applied log transformation to reduce skewness
- Standardized features using `StandardScaler`

### 4. Clustering
- Used **KMeans clustering**
- Determined optimal clusters using the **Elbow Method**
- Selected **4 clusters** for interpretability

---

## 👥 Customer Segments

- **Champions**  
  High frequency and high spending customers

- **At Risk (High Value)**  
  Previously valuable customers with declining engagement

- **New / Low Value**  
  Recently acquired or low-activity customers

- **Lost Customers**  
  Inactive customers with minimal contribution

---

## 📈 Key Insights

- A small group of customers contributes a large portion of revenue  
- High-value customers exist who are at risk due to reduced activity  
- New customers show growth potential but require engagement  
- Lost customers contribute minimal value and show high inactivity  

---

## 📊 Dashboard

The project includes an interactive Power BI dashboard that visualizes:
- Customer distribution by segment
- Average monetary value, frequency, and recency
- Segment-wise behavioral insights

<img width="1282" height="722" alt="Customer Segmentation Using RFM Analysis" src="https://github.com/user-attachments/assets/a843e5dd-647f-46a4-a482-42d338df3168" />


---

## 🛠 Tools & Technologies

- **Python** (Pandas, NumPy, Scikit-learn)
- **Power BI** (Data Visualization)
- **Jupyter Notebook**

---

## 🚀 Conclusion

This project demonstrates how customer segmentation using RFM analysis can help businesses:
- Identify high-value customers
- Detect at-risk customers early
- Design targeted marketing strategies

---

## 📬 Feedback

I’m actively improving my data analytics skills.  
Feel free to share feedback or suggestions!

## ✍️ Author

  Bharat Lalwani
