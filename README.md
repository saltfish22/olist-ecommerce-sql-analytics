# Olist E-Commerce SQL Analytics

An end-to-end SQL analysis project using **real e-commerce data** from [Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce), Brazil's largest department store marketplace. The dataset contains **100K+ orders** across **8 relational tables**, spanning 2016–2018.

## Project Overview

This project demonstrates the full data analytics workflow — from **relational database design** and **complex SQL queries** to **Python-powered visualizations**. It explores revenue trends, delivery performance, customer segmentation (RFM), seller reliability, and payment behavior using real-world data.


## Database 

| Table | Rows | Description |
|-------|------|-------------|
| `customers` | 99,441 | Customer demographics & location |
| `orders` | 99,441 | Order status, timestamps, delivery dates |
| `order_items` | 112,650 | Products, sellers, prices per order line |
| `order_payments` | 103,886 | Payment type, installments, amounts |
| `order_reviews` | 99,224 | Review scores and comments |
| `products` | 32,951 | Product dimensions and categories |
| `sellers` | 3,095 | Seller location data |
| `category_translation` | 71 | Portuguese → English category names |


## Visualizations

The dashboard (`dashboard.png`) includes 6 charts:

1. **Monthly Revenue Trend** — line chart showing growth trajectory
2. **Top 10 Categories** — horizontal bar chart of revenue by product category
3. **Payment Distribution** — pie chart of payment methods (credit card, boleto, etc.)
4. **Review vs Delivery** — combo chart correlating delivery speed with review scores
5. **Top States by Revenue** — bar chart of geographic revenue distribution
6. **RFM Customer Segments** — horizontal bar chart of customer value segments


## Key Findings

- **Revenue grew ~12x** from Jan 2017 to Nov 2017, then stabilized around R$1M/month
- **Health & Beauty and Watches** are the highest-revenue categories, while **Bed/Bath/Table** leads in order volume
- **Credit cards** account for ~74% of payments; boleto (bank slip) is the second most popular at ~19%
- **Strong negative correlation** between delivery delay and review scores — late deliveries see 2-3x more 1-star reviews
- **São Paulo (SP)** alone generates ~40% of total revenue, followed by RJ and MG
- **~97% of customers are one-time buyers** — huge opportunity for retention strategies
- **Pareto principle confirmed**: top 20% of categories generate approximately 80% of revenue


## Data Source

[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) — Real commercial data, anonymized. Released under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

