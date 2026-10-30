# 🛒 Amazon Sales Analysis — Power BI Dashboard

An interactive Power BI dashboard that tracks sales performance of Amazon products across categories, with time-intelligence measures (YTD and QTD), weekly and monthly trends, and product-level rankings.

> **Built by:** Sunil Luhar — MIS & Data Reporting | Power BI • Excel • SQL • Looker Studio
> **Live dashboard:** [Click here to view](PASTE-YOUR-POWER-BI-PUBLISH-TO-WEB-LINK-HERE)

---

## 📸 Dashboard Preview

![Amazon Sales Dashboard](screenshots/dashboard.png)

---

## 🎯 Project Objective

To convert raw Amazon order data into a clear sales dashboard that helps a business user answer questions such as:

- How much have we sold this year (YTD) and this quarter (QTD)?
- Which product categories bring the most revenue?
- Which individual products sell the most and get the most reviews?
- How do sales move month by month and week by week?

---

## 📊 Key Features

- **KPI cards:** YTD Sales, QTD Sales, YTD Products, YTD Reviews
- **Monthly trend:** Area chart of sales by month
- **Weekly trend:** Column chart of sales by week
- **Category table (matrix):** YTD sales, QTD sales and each category's share of total sales
- **Top products:** Bar charts of products by YTD sales and by YTD reviews
- **Interactive filters:** Slicers for Product Category and Quarter
- **Custom design:** Header, icons and a clean layout

---

## 🔎 Sample Insights

- The dataset has about **89,000 orders** from **January 2019 to December 2022**, with total sales of roughly **$8.4 million**.
- **Camera** is the top category by revenue (about **$2.48M**), followed by **Men Shoes (about $2.23M)** and **Men Clothes (about $1.17M)**.
- **Laptop** has far fewer orders than other top categories (about 1,000), but it still ranks fourth in revenue because of its high price per item.
- Yearly sales peaked in **2020 (about $3.1M)**.

*(Add your own 2–3 insights here after exploring the slicers.)*

---

## 🛠️ Tools & Skills Used

| Area | Details |
|---|---|
| Tool | Microsoft Power BI Desktop |
| Data preparation | Power Query (cleaning and data types) |
| Data modeling | Fact table (Amazon_Data) connected to a Date table |
| Calculations | DAX measures: YTD Sales, QTD Sales, YTD Products, YTD Reviews, % of total |
| Visuals | KPI cards, area chart, column chart, matrix, bar charts, slicers |
| Design | Custom layout, icons and consistent colors |

---

## 📁 Repository Structure

```
amazon-sales-powerbi-dashboard/
│
├── amazon_sales_dashboard.pbix     # Power BI report file
├── data/
│   └── Amazon_Combined_Data.xlsx   # Source data (orders)
├── screenshots/
│   └── dashboard.png
└── README.md
```

---

## 📂 Data Description

The source file `Amazon_Combined_Data.xlsx` has one sheet (`Amazon_Data`) with these columns:

| Column | Meaning |
|---|---|
| Product Category | Category of the product (8 categories) |
| Product Description | Name of the product |
| Price(Dollar) | Sales amount in US dollars |
| Number of reviews | Customer review count for the product |
| Shipment | Shipping destination |
| Order Date | Date of the order |

---

## ▶️ How to Open the Dashboard

1. Download or clone this repository.
2. Install **Power BI Desktop** (free) from Microsoft.
3. Open `amazon_sales_dashboard.pbix`.
4. If Power BI asks for the data source, go to **Home → Transform data → Data source settings** and point it to the Excel file in the `data/` folder.

---

## 📬 Contact

Available for freelance Power BI, Excel and reporting projects.

- **Name:** Sunil Luhar
- **LinkedIn:** [add your link]
- **Upwork:** [add your link]
- **Email:** [add your email]
