# Sales Dashboard using Tableau & Python

## Overview
This project presents an **interactive Sales Dashboard** built using **Tableau** and **Python**. It enables data-driven decision-making by visualizing key business insights such as revenue trends, regional sales performance, and customer behavior.

![Sales Dashboard](SalesDashboard.png)

## Technologies Used
- **Tableau** - Data visualization and dashboard creation
- **Excel/CSV** - Data source

## Features
- 📊 **Interactive visualizations** for sales trends, customer insights, and revenue analytics
- 📍 **Region-wise sales performance analysis**
- 📈 **Year-over-year growth trends**
- 🏷️ **Product category performance tracking**
- 🔍 **Filters and drill-down options for deeper insights**

## Project Structure
```
/SalesDashboard
│── data/
│   ├── sales_data.csv   # Raw sales data
│── scripts/
│   ├── data_cleaning.py # Preprocessing script in Python
│── dashboard/
│   ├── sales_dashboard.twb # Tableau dashboard file
│── README.md
```

## Installation & Setup
### Prerequisites
- **Tableau Desktop** (or Tableau Public)
- **Python 3.8+**
- Required Python Libraries: Pandas

### Steps to Run
1. **Clone the Repository**
   ```sh
   git clone https://github.com/iRahulGaur/SalesDashboard.git
   cd SalesDashboard
   ```
2. **Install Dependencies**
   ```sh
   pip install pandas
   ```
3. **Run Data Preprocessing Script**
   ```sh
   python scripts/data_cleaning.py
   ```
4. **Open the Tableau Dashboard**
   - Launch **Tableau Desktop**
   - Open `dashboard/sales_dashboard.twb`
   - Connect it to the cleaned dataset

## Key Visualizations
- **Revenue & Sales Trends** 📊
- **Customer Demographics & Segments** 👥
- **Profitability by Region & Category** 🌎
- **Monthly & Quarterly Performance Breakdown** 📆

## Future Enhancements
- Integrate **real-time sales data** from a database or API
- Automate data updates with **Tableau Prep**
- Deploy the dashboard on **Tableau Server or Tableau Public**

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---
Let me know if you have any questions or suggestions! 🚀
