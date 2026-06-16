# Walmart Store Analysis — Power BI Case Study
**Institution:** IVY Professional School  
**Tool:** Microsoft Power BI  
**Dataset:** Walmart 2022 & 2023 Sales Data  

## Objectives
- City-wise % contribution to Total Sales  
- Average Sales per Store in a City  
- Store Age vs Revenue analysis  
- City-wise Most Selling Product  

## Tech Stack
- Power Query (ETL & data cleaning)  
- DAX (measures & calculated columns)  
- Star Schema data modeling  
- Interactive dashboard with slicers  

## Key DAX Measures
- `Total Sales = SUM('Sales'[Weekly_Sales])`  
- `City % Contribution = DIVIDE(SUM, CALCULATE+ALL, 0)`  
- `Avg Sales Per Store = AVERAGEX`  
- `Store Age = DATEDIFF(Store_Open_Date, TODAY(), YEAR)`
