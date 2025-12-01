### **1. Sales Overview Dashboard**
- Total Customers  
- Total Orders  
- Reorder %  
- Average Basket Size  
- Orders by Day of Week  
- Orders by Hour of Day  
- Department-Level Volume  

**Screenshot:** `dashboards/instacart_sales_overview.png`

---

### **2. Customer Behavior Dashboard**
- Customer Segmentation (Heavy / Medium / Light Shoppers)  
- Retention Funnel (1st → 2nd → 3–5 → 6+ Purchases)  
- Reorder Probability by Segment  

**Screenshot:** `dashboards/instacart_customer_behavior.png`

---

### **3. Product Performance & Market Basket Dashboard**
- Top 10 Ordered Products  
- Top 10 Reordered Products  
- Market Basket Heatmap (Departments × Aisles)  

**Screenshot:** `dashboards/instacart_product_performance.png`

---

##  Highlights / Key Findings ( Summary)

### 🛒 **Customer Behavior**
- Heavy shoppers exhibit **68%+ reorder probability**.  
- A large portion of customers churn after their first order.  
- Retention significantly improves after the 2nd order.

###  **Product Insights**
- Bananas are the most commonly ordered and reordered product.  
- Organic produce dominates top product lists.  

###  **Market Basket Insights**
- Strong co-occurrence between Produce ↔ Dairy Eggs.  
- Snacks often appear with Beverages.  
- Frozen categories frequently pair with Pantry items.

---

##  Skills Demonstrated  
- Tableau Data Modeling (joins between orders, products, departments, aisles)  
- LOD Expressions  
  - `{ FIXED [user_id] : COUNTD([order_id]) }`  
- Cohort & Retention Funnel Analysis  
- Market Basket (co-occurrence) heatmaps  
- KPI creation and dashboard design  
- Data cleaning and dimension modeling  
- UX-oriented dashboard layout & filtering  

---

##  Dataset Notice  
The full Instacart dataset is not included in this repository due to size limits.  
A link to the Kaggle dataset is provided.  
Sample cleaned files are included in `data_sample/`.

---

##  How to Reproduce  
1. Download the Kaggle dataset.  
2. Open `tableau_workbook/instacart_dashboard.twbx` in Tableau Desktop.  
3. Update data connections to point to your local CSVs.  
4. Explore the dashboards and interact with filters.  
5. Replace sample CSVs with full dataset if needed.  

---

##  Contact  
For questions or collaboration:  
**Nikhil Mehalawat**  
 nikhilmehalawat@gmail.com  
