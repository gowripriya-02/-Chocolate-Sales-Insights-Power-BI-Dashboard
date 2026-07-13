📁 Repository Contents

FileDescriptionsample-data-10mins.xlsxRaw source dataset used to build the report10_mins_Power_BI_report.pbixPower BI Desktop file containing the interactive dashboard

📊 Dataset Overview — sample-data-10mins.xlsx

The workbook contains a single tab:

data tab (1,094 rows)

Transaction-level chocolate sales records with the following columns:

ColumnDescriptionSales PersonName of the salesperson responsible for the transactionCountryCountry where the sale took placeProductChocolate product sold (e.g., Mint Chip Choco, 85% Dark Bars)DateDate of the transactionAmountSales revenue generatedBoxes ShippedNumber of boxes shipped for the order

This dataset serves as the single source of truth for the Power BI report.

📈 Power BI Report — 10_mins_Power_BI_report.pbix

A one-page interactive dashboard with four core visuals:


Boxes Shipped by Country (Column Chart) — compares shipping volumes across countries to highlight top markets.
Boxes Shipped by Product (Bar Chart) — ranks products by total boxes shipped to identify best-sellers.
Sales Amount Trend (Line Chart) — tracks revenue over time using a Year → Quarter → Month → Day drill-down hierarchy.
Sales Amount by Product Over Time (Waterfall Chart) — visualizes how each product contributes to overall revenue movement.


🎯 Purpose

This project demonstrates the ability to go from a flat, unprocessed dataset to a functional, insight-driven BI report quickly — covering data import, visual selection, chart configuration, and basic time-intelligence drill-downs in Power BI.

🛠️ Tools Used


Microsoft Excel (data source)
Microsoft Power BI Desktop (data visualization & reporting)


🚀 How to Use


Clone this repository.
Open 10_mins_Power_BI_report.pbix in Power BI Desktop.
Explore the dashboard, or refresh the data connection using sample-data-10mins.xlsx as the source.



