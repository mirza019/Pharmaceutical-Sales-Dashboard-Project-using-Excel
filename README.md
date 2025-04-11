# 💊 Pharmaceutical Sales Dashboard Project
A full-featured data analytics and dashboard project that explores synthetic pharmaceutical sales data across multiple countries, products, and sales channels. The project is ideal for showcasing Excel and Power BI skills.

---

## 📁 Project Summary
- **Objective**: To simulate and analyze pharmaceutical sales data for deriving actionable insights using Excel and Power BI.
- **Dataset Size**: 1,000 rows of synthetic records
- **Scope**: Covers 5 products, 5 countries, 2 sales channels, and 5 sales representatives over a year (2024).
- **Tools Used**: Python (Pandas, XlsxWriter), Excel (Charts, Dashboards), Power BI (for visualization).

---

## 🧾 Dataset Details
Each row in the dataset represents an individual sales transaction with the following attributes:

### 📄 Columns Breakdown
| Column Name       | Data Type | Description | Example Values |
|------------------|-----------|-------------|----------------|
| `Date`           | Date      | Date of transaction (monthly, 2024) | `2024-03-31`, `2024-10-31` |
| `Region`         | String    | Country where sale occurred | `Germany`, `France`, `Italy` |
| `Product`        | String    | Type of pharmaceutical product | `Vaccine`, `Insulin` |
| `Channel`        | String    | Sales channel used | `Pharmacy`, `Hospital` |
| `Sales Rep`      | String    | Sales representative responsible for sale | `Rep A`, `Rep E` |
| `Units Sold`     | Integer   | Number of units sold | `15`, `240` |
| `Unit Price (€)` | Float     | Price per product unit in Euros | `34.5`, `79.0` |
| `Revenue (€)`    | Float     | Calculated Revenue = Units Sold × Unit Price | `3450.00` |

---

## 📊 Excel Dashboard Features
The Excel dashboard includes dynamic and diverse visualizations to provide actionable business insights:

- 📌 **Revenue by Country** – Clustered Column & Bar Charts
- 📈 **Sales Rep Revenue Trend** – Line Chart
- 📊 **Units Sold vs Average Unit Price** – Combo Chart (Column + Line)
- 🧱 **Product Revenue by Channel** – Stacked Column & 100% Stacked Charts
- 🍩 **Channel Revenue Share** – Pie and Doughnut Charts
- 🔢 **Units Sold by Product** – Vertical Column Chart
- 📆 **Monthly Product Revenue** – Date-wise visualization (supports time analysis)

The dashboard includes autofilters, formatted headers, and map-ready region fields.

---

## 🌍 Power BI Readiness
The dataset is structured to support advanced Power BI use cases:
- Map visualizations using the `Region` column
- Date slicers from `Date` column
- Grouping and filtering across `Product`, `Sales Rep`, and `Channel`
- KPI cards for Total Revenue, Avg Unit Price, and Units Sold

---

## 📈 Example Use Cases
- Determine which countries drive the most revenue
- Compare performance between hospitals and pharmacies
- Identify top-performing products and sales representatives
- Visualize revenue trends and pricing over time
- Support strategic planning and marketing allocation

---

## 🛠 Tools & Technologies
- **Python**: Used to simulate data and generate Excel dashboards using `pandas` and `xlsxwriter`
- **Excel**: For dashboard creation with charts, pivots, slicers, and KPIs
- **Power BI**: For enhanced dashboard interactivity and geographic visualizations

---

## 📌 File Downloads
- Excel Dashboard : `Pharma_Sales_Dashboard.xlsx`
- Power BI CSV: `Pharma_Sales_PowerBI_Dataset.csv`

---
_Created by Mirza Shaheen Iqubal_  
_M.Sc. in Data Science (FAU Erlangen-Nürnberg)_
