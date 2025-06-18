# 🛒 Retail Analytics Case Study

A full end-to-end data analysis of a mid-size retailer’s sales, customers, and inventory.  
The notebook answers three core business questions:

1. **Product performance** – Which SKUs drive revenue? What are the month-over-month trends?  
2. **Customer segmentation** – Orders, spend, quantity, loyalty tiers, and classic RFM profiles.  
3. **Customer behaviour** – Repeat-purchase patterns & actionable loyalty insights.

**Deliverables:** a runnable Jupyter notebook (`retail_case_study.ipynb`), a lightweight SQLite DB, and three cleaned CSV exports ready for downstream use.

---


📝 Notebook highlights

| Section  | What you’ll see                                                               |
| -------- | ----------------------------------------------------------------------------- |
| **0-3**  | Data loading, sanity checks, cleaning (duplicates, nulls, price mismatch fix) |
| **4**    | SQLite staging for fast SQL (top sellers, Mo-M trend)                         |
| **5-6**  | Product performance table + category revenue viz                              |
| **7-11** | Customer segments: Orders, Spend, Loyalty, Quantity                           |
| **12**   | **RFM segmentation** with Champion / Loyal / At-risk labels                   |
| **13**   | Month-over-month revenue + growth plot                                        |
| **14**   | CSV exports for cleaned sales, enriched customer table, product performance   |


💡 Business takeaways (TL;DR)

15 % of SKUs contribute ~70 % of revenue—focus promo budgets there.

“Champions” (RFM score ≥ 13) represent 8 % of customers but 35 % of sales—priority for loyalty perks.

Mo-M revenue dip in August (-7 %) correlates with low stock on two high-margin categories—inventory alert set.

Read the inline Markdown cells for more context & next-step recommendations.
