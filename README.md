📊 **Sales Dashboard – Power BI with SSAS Live Connection**

This repository contains a Power BI project titled Sales Dashboard, built on a live SSAS (SQL Server Analysis Services) model to provide real-time reporting on national sales performance.


🧩 **Data Model Overview**
The semantic model connects multiple dimension and fact tables with proper relationships to support slicing by:

1. Date
2. Product
3. Market
4. Division
5. Region
6. Business Type


⚙️ **Project Highlights**
🔗 Live connection to SSAS for real-time data refresh

📅 Dynamic filtering by date, zone, region, division, product type, and brand

📐 Fully relational data model with best practices (star schema style)

🌐 Optimized for high performance and low latency in Power BI Service 

📐 Fully relational data model with best practices (star schema style)

🌐 Optimized for high performance and low latency in Power BI Service


📈 **Visual KPIs including:**

  1. Budget vs Sales Comparison
  2. Cumulative Achievements
  3. Year-over-Year Growth
  4. Top/Bottom Performance by Zone, Region, and Market



**🗃 Folder Structure**

powerbi-sales-report/
├── README.md
├── SalesDashboard.pbix            # Optional - not committed here
├── Model/
│   ├── Model.bim                  # Exported using Tabular Editor
│   ├── Measures.dax               # DAX measures for calculations
├── SSASConnection/
│   ├── connection_config.json     # Connection info (no credentials)
├── Documentation/
│   ├── DataModelDiagram.png       # Screenshot of data model
│   ├── SalesDashboard.png         # Full dashboard view
│   ├── UserGuide.md               # How to use and maintain
├── Scripts/
│   ├── refresh_api_trigger.ps1    # Optional: to refresh dataset
│   └── metadata_extractor.py      # For extracting model info


**🧠 Key Technologies**
1. Power BI Desktop
2. SSAS (Tabular Model)
3. DAX
4. Tabular Editor (for metadata versioning)
5. Git + GitHub for source control


**📦 How to Use**

1. Clone this repository
2. Open SalesDashboard.pbix (not included by default)
3. Ensure you have access to the SSAS server listed in SSASConnection/connection_config.json
4. Explore or publish to Power BI Service


**🚫 Notes**
1. .pbix file is not committed to the repo due to size & security
2. No sensitive credentials are stored
3. Live connection requires internal access to SSAS server
