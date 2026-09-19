# Learners-Dashboard-Dataset
Learners Dashboard Dataset

A normalized relational retail dataset modeling global sales, inventory health, fulfillment operations, and accounts receivable across scale-model vehicle lines. This repository includes the relational schema, key performance indicators, analytical findings, and an accompanying interactive Power BI dashboard (`Learners Dashboard.pbix`)[cite: 1, 3].

---

## 📁 Repository Structure

```text
├── data/
│   ├── customers.csv         # 122 B2B accounts, geographic attributes, credit limits
│   ├── employees.csv         # 23 internal personnel, sales reps, organizational hierarchy
│   ├── offices.csv           # 7 regional corporate offices and regional territories
│   ├── order details.csv     # 2,996 line items (quantity, unit sale price, line position)
│   ├── orders.csv            # 326 orders, order dates, fulfillment statuses, target dates
│   ├── payments.csv          # 273 recorded customer remittance transactions
│   ├── productlines.csv      # 7 high-level categories and catalog descriptions
│   └── products.csv          # 110 SKUs, inventory counts, buy price, MSRP
├── dashboard/
│   └── Learners Dashboard.pbix # Interactive multi-page Power BI report file
└── README.md
