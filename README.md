# StarSchema-Sales-Dashboard

This dashboard is powered by a **Star Schema** model in Power BI, enabling clean, efficient relationships between data tables.

### ✅ Fact Table
- `FactSales`: Stores transactional sales data including profit, quantity, and tax info.

### ✅ Dimension Tables
- `DimCustomer`: Customer and demographic information
- `DimEmployee`: Sales reps and employee data
- `DimDate`: Calendar table for time-based analysis
- `DimCity`: Geographic locations (city/state/province)
- `DimStockItem`: Product and packaging info

This modeling structure improves:
- Query performance
- DAX calculation simplicity
- Data slicing and cross-filtering

