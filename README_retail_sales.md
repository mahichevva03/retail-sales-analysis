# 🛒 Retail Sales Performance Analysis

**Tool:** Python (Pandas, Matplotlib, Seaborn)  
**Author:** [Maheshwari Chevva](https://github.com/mahichevva03)  
**LinkedIn:** [linkedin.com/in/maheshwari-chevva-6320372a9](https://www.linkedin.com/in/maheshwari-chevva-6320372a9)

---

## 📌 Project Objective

Build and analyse a multi-region retail sales dataset to simulate real-world sales BI reporting. The project covers data generation, cleaning, feature engineering, and visualisation — producing insights on monthly revenue trends, regional performance, and top products.

---

## 📊 Dataset

**Generated using:** Python `Faker` library  
**Size:** 200 rows  

| Column | Description |
|---|---|
| `OrderID` | Unique order identifier |
| `Date` | Order date (last 1 year) |
| `CustomerID` | UUID customer identifier |
| `Products` | Product name |
| `Category` | Product category |
| `Quantity` | Units ordered (1–5) |
| `UnitPrice` | Price per unit (100–1000) |
| `TotalPrice` | Quantity × Unit Price |
| `Region` | North / South / East / West |

**Products:** Laptop, Phone, Tablet, Headphones, Camera  
**Categories:** Electronics, Accessories, Gadgets  
**Regions:** North, South, East, West

---

## 🔍 Analysis Performed

### Data Preparation
- Generated synthetic data using `Faker` and `random`
- Parsed `Date` column to datetime
- Engineered `Revenue` column (Quantity × UnitPrice)
- Extracted `Month` and `Year` features

### Business Questions Answered
1. What is the monthly revenue trend over the past year?
2. Which products generate the highest total revenue?
3. How is revenue distributed across regions?

---

## 📈 Visualizations

| Chart | Insight |
|---|---|
| Line chart — Monthly Revenue Trend | Revenue trajectory by year and month |
| Bar chart — Top 5 Products by Revenue | Best-performing products |
| Pie chart — Regional Sales Distribution | Revenue share by region |

---

## 💡 Key Findings

- Revenue trends reveal seasonal fluctuation across months
- Top products consistently account for a disproportionate share of total revenue
- Regional distribution highlights which geographies drive the most sales volume

---

## 🛠️ Libraries Used

```python
pandas · numpy · matplotlib · seaborn · faker · random
```

---

## 📁 Files

| File | Description |
|---|---|
| `sales.ipynb` | Full analysis notebook |
| `sales_data.csv` | Auto-generated dataset (created on first run) |

---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies: `pip install faker pandas matplotlib seaborn`
3. Open `sales.ipynb` in Jupyter Notebook or VS Code
4. Run all cells — the dataset is auto-generated on first run
