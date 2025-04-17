## 🎯 Objective
Analyze sales data for tech products stored in a SQLite database using Python. Generate a summary and visualize the revenue using a bar chart.

## 🛠 Tools Used
- Python
- SQLite (`sqlite3`)
- pandas
- matplotlib
- Jupyter Notebook

## 📦 Dataset
The dataset contains fictional sales data for tech products such as:
- Wireless Mouse
- Mechanical Keyboard
- HD Monitor
- USB-C Hub
- External SSD

Each row in the database includes:
- `product` name
- `quantity` sold
- `price` per unit

## 🧠 What I Did
- Created a SQLite database (`sales_data.db`) and added sample tech product sales data.
- Wrote an SQL query to calculate total quantity sold and revenue for each product using `GROUP BY`.
- Loaded the result into a pandas DataFrame.
- Displayed the result with `print()`.
- Visualized product revenue using a matplotlib bar chart.
- Saved the chart as `sales_chart.png`.

## 📊 Output

### ▶ Sales Summary (Example Output)
| Product              | Total Qty | Revenue  |
|----------------------|-----------|----------|
| Wireless Mouse       | 35        | ₹559.65  |
| Mechanical Keyboard  | 22        | ₹1,001.00|
| HD Monitor           | 15        | ₹1,800.00|
| USB-C Hub            | 30        | ₹750.00  |
| External SSD         | 12        | ₹1,079.88|

### 🖼 Bar Chart
A bar chart of revenue by tech product is generated and saved as `sales_chart.png`.

## 📁 Files Included
- `sqlite_jupyter.ipynb` – Jupyter Notebook
- `sales_data.db` – SQLite Database
- `sales_chart.png` – Output Bar Chart
- `README.md` – This file
