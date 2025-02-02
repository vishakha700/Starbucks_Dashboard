# Starbucks Sales Dashboard Analysis

### **1. Data Extraction**
The raw data was directly used without performing extensive cleaning. The focus was on transforming the available columns to create meaningful insights.

#### **Steps:**
1. **Extracted Key Time Components:**
   - **Date, Day, Hour:** These were derived from a `Transaction Time` column to analyze trends by time.
2. **Calculated Revenue:**
   - Formula: `Revenue = Quantity × Unit Price`
3. **Prepared Measures:**
   - Created measures like total revenue, total quantity sold, and average price per order using Power BI’s DAX.



### **2. Dashboard Visualizations**
The Power BI dashboard consists of multiple charts, each providing insights into Starbucks’ sales performance.

#### **Visuals and Insights:**

1. **Top Cards:**
   - **Average Order per Person:** Displays the approximate number of orders per customer (Value: 1).
   - **Total Units Sold:** Aggregates all quantities sold across all products (Value: 243K).
   - **Average Price per Order:** Average price calculated from total revenue divided by units sold (Value: ₹306).
   - **Total Revenue:** Total revenue generated by all transactions (₹70.6M).

2. **Sales by Hour:**
   - Line chart showcasing sales trends across different hours of the day.
   - **Peak Hours:** 9 AM to 10 AM (₹9M) suggests high demand during breakfast hours.
   - **Low Hours:** Post-noon sales drop significantly, hitting the lowest at 8 PM (₹0.3M).

3. **Sales by Month:**
   - Line chart showing revenue growth over six months.
   - Steady increase from January (₹8.3M) to June (₹16.8M), indicating seasonal growth.

4. **Sales by Day:**
   - Line chart highlighting revenue trends for each day of the week.
   - **High Revenue Days:** Tuesday (₹10.26M) and Friday (₹10.25M).
   - **Low Revenue Day:** Sunday (₹9.91M).

5. **Total Quantity Sold by Category:**
   - Bar chart displaying the number of units sold by product category.
   - **Top Category:** Coffee (92,512 units).
   - **Low-Selling Categories:** Packaged Chocolate (487 units) and Loose Tea (1,210 units).

6. **Revenue by Product Category:**
   - Bar chart comparing revenue across product categories.
   - **Highest Revenue:** Coffee (₹23M).
   - **Lowest Revenue:** Packaged Chocolate (₹0.3M).

7. **Sum of Revenue by Store Location:**
   - Bar chart representing revenue generated by different stores.
   - **Top-Performing Stores:** IGI Airport, Connaught Circle, and Paschim Vihar (~₹23M each).



### **3. Insights and Recommendations**

#### **Key Insights:**
1. **Time-Based Trends:**
   - Morning hours are most profitable. Sales drop significantly after noon.
2. **Product Performance:**
   - Coffee and Tea dominate both in quantity and revenue.
   - Packaged products contribute the least.
3. **Day-Wise Trends:**
   - Weekdays like Tuesday and Friday generate more revenue compared to weekends.
4. **Store Locations:**
   - All top stores perform similarly; deeper analysis can reveal growth opportunities.

#### **Recommendations:**
1. **Promotions for Low-Sales Hours:**
   - Offer discounts or combo deals during post-noon hours to boost sales.
2. **Focus on High-Selling Categories:**
   - Optimize inventory and marketing for Coffee and Tea.
3. **Boost Sunday Sales:**
   - Introduce weekend-specific promotions or loyalty programs.
4. **Expand Analysis to More Stores:**
   - Explore why revenues are similar across top stores and identify areas for expansion or improvement.

---

### **4. Tools Used**
- **Data Extraction and Transformation:** Power BI Query Editor.
- **Visualization:** Power BI.
- **DAX Measures:** Used for calculating key metrics such as average price, total revenue, etc.


![Screenshot 2025-01-20 120951](https://github.com/user-attachments/assets/1e622f93-8480-409c-b4ff-59039f29cc39)
