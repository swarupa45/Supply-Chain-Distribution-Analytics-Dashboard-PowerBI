# Supply-Chain-Distribution-Analytics-Dashboard-PowerBI
A Power BI dashboard to analyze supply chain performance, delivery efficiency, and distribution metrics.
## Global Biscuits Supply Chain & Logistics Operations Dashboard
<img width="1305" height="688" alt="Executive KPI overview" src="https://github.com/user-attachments/assets/bb2b9ed5-ba37-4e6b-aaf8-1e35379417aa" />


### 🔍 View Remaining Dashboard Pages
<details>
<summary><b>💡 Click here to expand and view pages 2, 3, and 4</b></summary>

### Page 2: Supply Chain & Logistics Trends
<img width="1312" height="758" alt="Supply chain and Logistic trends" src="https://github.com/user-attachments/assets/f2960030-f1a5-499c-ade7-e6b9e8fa6511" />


### Page 3: Product Profitability & Margins
<img width="1311" height="698" alt="Product margins" src="https://github.com/user-attachments/assets/27b1e313-ac64-4619-a63d-0d4700249bb4" />


### Page 4: Regional & Geography Analytics
<img width="1316" height="739" alt="Regional Analytics" src="https://github.com/user-attachments/assets/23eac42c-82e6-4a3f-afa6-7aff6a901514" />


## 📌 Project Overview
Developed an enterprise-grade interactive Power BI dashboard to optimize distribution networks, reduce freight overheads, and audit product line profitability for a global biscuits manufacturing and distribution firm.

## 🛠️ Technical Workflow & Architecture
* **Data Ingestion & ETL:** Cleaned and profiled raw transactional data within **Power Query**. Performed advanced **Data Masking using custom M-Code** to map proprietary product catalogs into a standardized commercial biscuit portfolio (`Premium Butter Cookies`, `Dark Bourbon Cracker`) for enterprise data compliance.
* **Data Modeling:** Established a highly optimized **Star Schema** data model in Model View, enforcing clean One-to-Many (`1 to *`) relationships between the central supply chain fact table and localized lookup dimensions (`calendar`, `products`, `geography`, `persons`).
* **Advanced Analytics (DAX):** Authored explicit reusable DAX measures (`Total Revenue`, `Total Transport Cost`, `SupplyChain Margin %`) leveraging **SUMX** and **RELATED** cross-table iterators. Engineered an automated **Low-Box Shipment Alert system** using `COUNTROWS(FILTER(... < 50))` to flag under-utilized freight containers and eliminate transport wastage.
* **UI/UX & Performance:** Built a responsive modern 5-page layout featuring executive KPI cards, time-series line graphs for capacity planning, and agent matrix leaderboards. Integrated global **Sync Slicers** behind a centralized geography filter pane to maximize visual canvas real estate.

## 📊 Dashboard Architecture (5-Page Layout)
1. **Executive KPI Overview:** High-level financial health auditing for C-suite stakeholders.
2. **Logistics Trends:** Deep-dive fulfillment monitoring, route auditing, and freight load optimization alerts.
3. **Product Margins:** Portfolio profitability ranking, isolating high-margin vs negative-margin biscuit products.
4. **Geography Analytics:** Territorial revenue mapping powered by centralized cross-page Sync Slicers.
5. **Sales Leaderboard:** Interactive agent matrix leaderboard utilizing dynamic drill-down hierarchies.
