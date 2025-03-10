# 📊 CityLife 360° Power BI Dashboard
#### *A Data-Driven Approach to Advisor & Product Performance Analysis*

---

## **🌍 Problem Statement**
CityLife, a leading insurance company, aims to **gain a 360-degree view of its Wealth & Insurance business** to improve decision-making.  
The business leadership requested a **dashboard that provides insights into advisor performance and product sales trends** to help drive **growth, optimize product strategies, and enhance customer experience**.

To meet this goal, we developed a **Power BI dashboard** that provides:
- **Advisor Performance Metrics** (Regional comparisons, top/bottom performers)
- **Product Performance Analysis** (Sales trends, customer demand, and profitability)
- **Overall Business Overview** (Sales, Withdrawals, and Net Sales insights)

---

## **📌 Project Requirements**
1. **Data Sources**  
   - Excel file (`CityLife data.xlsx`) containing raw sales, advisor, and product data.  
2. **Dashboard Expectations**  
   - A **comprehensive overview** of Wealth & Insurance business.  
   - Breakdown of **advisor performance by region and individual performance**.  
   - Insights into **product sales, customer preferences, and profitability**.  
   - Ability to **filter data dynamically** for better decision-making.  
3. **Technology Used**  
   - **Power BI** (Data visualization & modeling)  
   - **Excel** (Data preprocessing & storage)  

---

## **🛠️ Steps Done (Methodology)**  
### **🔹 Step 1: Data Collection & Preparation**  
- Loaded the **Excel dataset** into Power BI.  
- Checked **data consistency** and performed **data cleaning** (handling missing values, standardizing formats).  
- Established **relationships** between key tables (Sales, Advisors, Products).  

### **🔹 Step 2: Data Modeling & DAX Calculations**  
- Created **calculated columns & measures** to compute:
  - **Total Sales**
  - **Total Withdrawals**
  - **Net Sales** (`Sales - Withdrawals`)
  - **Advisor Performance Metrics**  
- Implemented **DAX measures** for dynamic analysis.  

### **🔹 Step 3: Dashboard Design & Visualization**  
- Designed **three key pages**:
  1. **Company Overview** – High-level insights (Total Sales, Net Sales, Withdrawals).  
  2. **Advisor Performance** – Top-performing advisors, regional comparisons.  
  3. **Product Analysis** – Best-selling products, profitability insights.  
- Added **slicers & filters** for interactive analysis.  

### **🔹 Step 4: Performance Optimization & Finalization**  
- Optimized **DAX queries** for faster report loading.  
- Ensured **user-friendly navigation** with clear KPIs and trends.  
- Validated insights with stakeholders.  

---

## **📊 Key Insights from the Dashboard**  
### ✅ **1. Advisor Performance Insights**  
- Certain **advisors in specific regions outperform others**, highlighting areas where training or hiring could be improved.  
- **Top 10 advisors** contribute to a significant portion of overall sales.  

### ✅ **2. Product Sales Trends**  
- **Some products consistently generate high revenue**, while others have low adoption rates.  
- Product demand varies **seasonally**, impacting profitability and marketing strategies.  

### ✅ **3. Sales & Withdrawals Breakdown**  
- **High withdrawal rates** in certain regions indicate **customer dissatisfaction** or **policy lapses**.  
- **Net Sales trends** reveal which business areas are profitable vs. underperforming.  

### ✅ **4. Data-Driven Business Growth Opportunities**  
- Identifying **low-performing advisors** can lead to **targeted performance improvement programs**.  
- Focusing on **best-selling products** can help optimize inventory and marketing.  
- Reducing withdrawal rates can **enhance customer retention strategies**.  

---

## **📂 Project Files**  
| File Name                        | Description |
|----------------------------------|-------------|
| `data/CityLife data.xlsx`        | Raw dataset containing sales, advisors, and products |
| `reports/Final Project City Life 360.pbix` | Power BI dashboard with all visualizations and analysis |

---

## **🚀 Setup & Usage**  
1. **Clone this repository**:
   ```sh
   git clone https://github.com/YOUR-USERNAME/CityLife-PowerBI.git
   ```
2. **Open the Power BI file**:  
   - `Final Project City Life 360.pbix` in **Power BI Desktop**.  
   - Ensure `CityLife data.xlsx` is properly linked.  
3. **Explore the Dashboard**:
   - Use filters to **analyze Advisor & Product performance dynamically**.  
   - Drill down into **Sales, Withdrawals, and Net Sales insights**.  

---

## **📌 Future Enhancements**  
- Add **machine learning predictions** for **future sales trends**.  
- Implement **real-time data refresh** via cloud-based solutions.  
- Improve UI/UX for **better navigation & interactive insights**.  

---

## **💎 Contact**  
For any queries, reach out at **[your.email@example.com](mailto:your.email@example.com)**.  

---

### ✅ **Now, Follow These Steps to Upload to GitHub**  
1. **Ensure the following files are in your project folder**:  
   ```
   CityLife-PowerBI/
   │── data/
   │   └── CityLife data.xlsx
   │── reports/
   │   └── Final Project City Life 360.pbix
   │── README.md
   │── .gitignore
   ```
2. **Run these Git commands to upload**:
   ```sh
   cd path/to/your/CityLife-PowerBI
   git init
   git add .
   git commit -m "Initial upload of CityLife Power BI project"
   git remote add origin https://github.com/YOUR-USERNAME/CityLife-PowerBI.git
   git branch -M main
   git push -u origin main
   ```
3. **Share your GitHub repository link** after uploading! 🚀  

Let me know if you need further improvements!
