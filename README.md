# E-Commerce Analytics Dashboard — Power BI

## 📌 Project Overview
An interactive business intelligence dashboard built in Power BI to analyze a Brazilian e-commerce dataset. The project covers end-to-end data cleaning, transformation, and visualization to surface insights across sales, logistics, seller performance, and customer satisfaction.


## 🗂️ Dataset
- **Source:** E-Commerce dataset
- **Size:** ~15,000 rows, 44 columns
- **Coverage:** Orders, products, sellers, payments, freight, and customer reviews

**Key columns include:**
- `order_id`, `order_status`, `order_purchase_timestamp`
- `customer_state`, `seller_state`, `seller_city`
- `price`, `freight_value`, `payment_type`
- `review_score`, `product_category_name`
- `product_description_lenght`

---

##  Data Cleaning 
- Removed duplicate and null records
- Corrected data types for timestamp and numeric columns
- Resolved duplicate payment columns (`payment_sequential_x/y`)
- Parsed and formatted date/time fields for time intelligence
- Standardized product category names using the English translation column


## Key Visualizations

| Visual | Insight |
|---|---|
| Average Review Score by Category | Top categories (CDs, fashion, tablets) score 5.0 |
| Top 5 Sellers by Revenue | Identifies highest revenue-generating seller IDs |
| Freight Value by Region (Pie Chart) | 77% of freight concentrated in São Paulo |
| Avg Delivery Time by Seller State | Compares ES, MS, PB state delivery performance |
| Cities with Highest Seller Activity | São Paulo dominates seller presence |
| Product Description Length vs Review Score | Scatter plot showing correlation |
| Category with High Review Score | Ranked bar chart of top-rated categories |
| Credit Card Review Growth | −1.77% growth trend indicator |

---

## Key Insights
- **77%** of total freight value originates from São Paulo, indicating heavy logistics concentration
- Categories like **CDs/DVDs, fashion children's, and tablets** consistently achieve perfect 5.0 review scores
- Average order **approval time is 7.03 hours**
- Seller activity is heavily concentrated in **São Paulo city**

---

## 🛠️ Tools Used
- **Power BI Desktop** — Dashboard design and DAX measures
- **Power Query** — Data cleaning and transformation
- **Microsoft Excel / CSV** — Raw data source

---

## 🚀 How to View
1. Download the `.pbix` file
2. Open with [Power BI Desktop](https://powerbi.microsoft.com/desktop)
3. Explore the interactive dashboard

---

## 👤 Author
**Ritvik Gulati**
[LinkedIn](www.linkedin.com/in/ritvik-gulati-0a822b32a) | [GitHub](https://github.com/ritvikgulati297)
