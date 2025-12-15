# 🧾 Customer Segmentation and Behavioral Analysis using RFM and Demographic Profiling

## 📌 Overview
This project performs customer segmentation for a Walmart dataset using **Frequency and Monetary (FM)** analysis along with demographic profiling. The goal is to identify distinct customer groups based on **purchase behavior** and **demographic traits**, enabling personalized marketing strategies and improving customer retention.

---

## 🎯 Objective
To uncover actionable insights about customer value and engagement by:
- Segmenting customers using **Frequency and Monetary** scores
- Analyzing **demographic variables** like age, gender, city, and marital status
- Understanding product preferences within each segment
- Providing data-driven **recommendations** to optimize loyalty and marketing

---

## 🔄 Process & Methodology

### 1. Data Cleaning & Preparation
- Removed duplicates and handled blank values
- Ensured completeness of transactional and demographic fields
- Standardized product and customer identifiers
- Find out who are our customers and their demographics
  <img width="1427" height="1080" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/2f320dba-f061-40ce-aaad-e81afd084610" />


### 2. FM Scoring & Segmentation
- **Frequency**: Total number of transactions per customer
- **Monetary**: Total spending per customer
- Used **percentile-based scoring** (scale: 1–3) for both F and M metrics
- Generated FM combinations (e.g., 33, 21, 12)
- Mapped FM scores to 4 behavioral segments:
  - **Champions**
  - **Potential Loyalists**
  - **Needs Attention**
  - **At Risk**
    <img width="1437" height="1080" alt="Screenshot (58)" src="https://github.com/user-attachments/assets/cc69162d-2d64-466c-b160-96b8ffcb7efc" />


### 3. Demographic Profiling
- Cross-tabulated segment distribution by:
  - **Gender**
  - **Age Bracket**
  - **City Tier**
  - **Marital Status**
- Calculated **representation index** to detect over/under-representation in each group

### 4. Product Category Analysis
- Identified most and least preferred product categories within each segment
- Tracked which demographics favor which product types
- Flagged potential cross-sell and up-sell opportunities

---

## 🧭 Key Steps Involved

- Data exploration and cleanup using Excel
- Created **Pivot Tables** for frequency and monetary values
- Applied **percentile logic** for FM scoring
- Built lookup-based segment assignment system
- Conducted demographic indexing and summary tables
- Designed visuals and exportable summaries for presentation

---
## 🧍‍♂️ Customer Personas & Strategic Takeaways

### 🔑 Key Personas Identified

1. **Engaged Young Shoppers**
   - High-potential group with strong engagement
   - Responsive to loyalty programs and gamified offers

2. **Curious Mid-Age Buyers**
   - Frequent buyers exploring various product categories
   - Ideal for personalized recommendations and cross-sell opportunities

3. **Value-Conscious Low Engagers**
   - Price-sensitive with low transaction frequency
   - Target with time-limited discounts and bundle deals

4. **Disengaged Customers**
   - Low frequency and low monetary value
   - Re-engage with awareness campaigns and product education

---
<img width="1434" height="1080" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/a249434f-5c86-4667-8215-5ab1d9c45d3b" />




## ✅ Strategic recommendations and Takeaways

<img width="2554" height="411" alt="image" src="https://github.com/user-attachments/assets/0f695a32-6a1f-4164-bd04-5ebc7dca0a14" />

  <img width="1434" height="1080" alt="Screenshot (56)" src="https://github.com/user-attachments/assets/bbe4888a-87e3-4ed0-8e8b-3b686bbae0d1" />

     

---

## 🛠️ Tools & Techniques Used

| Tool          | Purpose                                  |
|---------------|------------------------------------------|
| **Excel**     | Pivot Tables, IF/VLOOKUP formulas, Percentile logic |
| **FM Scoring**| Customer segmentation framework          |
| **Indexing**  | Demographic over/under-representation    |
| **Charting**  | Segment distributions and visuals        |

---

## 📎 Outcome
This project enabled data-driven segmentation of customers using just transactional count and spend metrics. Combined with demographic profiling, it offered **clear visibility into high-value and disengaged customer clusters**, equipping the business with actionable strategies to boost revenue, improve retention, and personalize offerings.

---
## NOTE-  Detailed project can be viewed in PPT,Excel file attached above.

