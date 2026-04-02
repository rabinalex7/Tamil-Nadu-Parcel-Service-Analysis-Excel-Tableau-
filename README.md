# Tamil Nadu Parcel Service Analysis (Excel-Tableau)
Logistics &amp; Supply Chain analysis of 250,000+ parcel records across Tamil Nadu. Utilizing Excel and Tableau, this project tracks delivery performance, shipping costs, and regional logistics hubs. Features include delivery status monitoring (Cancelled/Pending/Returned/In Transit/Delivered), and district-wise revenue distribution.

## 1. Project Overview
This project is a deep-dive into Logistics & Supply Chain Analytics, focusing on a parcel service provider operating across 30+ districts in Tamil Nadu. By processing over 256,000 transactions, the project identifies operational efficiencies, revenue hotspots, and delivery performance metrics.

## 2. Core Business Questions Addressed
You structured this project to answer specific logical and aggregation questions, which is a major highlight for your portfolio:

Revenue Analysis: Which districts (e.g., Erode, Chennai, Tirunelveli) are the primary drivers of shipping cost revenue?

Operational Health: What is the distribution of "In Transit" vs. "Returned" vs. "Delivered" parcels?

Product Insights: How do different parcel types (Medical, Electronics, Furniture, etc.) vary in weight and cost?

Performance Tracking: How does the delivery volume trend month-over-month between 2024 and 2025?

## 3. Technical Implementation
### Data Engineering (Excel)
Volume Handling: Cleaned and managed 250,000+ records without performance loss.

Advanced Logic: Utilized IFS and AND functions to create custom categories:

Weight Categorization: 0-5Kg to 45-50Kg equally 5Kg split and analysed the Parcel Status Based on their Weights

Pivot Table Modeling: Generated multi-dimensional summaries for Monthly Parcel Counts and District-wise Average Weights.

### Visual Intelligence (Tableau)
Relational Mapping: Connected the parcel data to visualize "From-To" district pairs and identify the busiest logistics corridors.

Dashboard Interactivity: Built dynamic filters allowing users to drill down by Parcel Type and Delivery Status.

Trend Analysis: Created time-series visualizations to track the ₹347M vs ₹306M cost growth between 2025 and 2024.

## 4. Key Strategic Insights
Regional Hubs: Erode and Dindigul were identified as the highest parcel-sending districts, while Namakkal and Tirunelveli were the top receiving hubs.

Weight Distribution: Medical and Groceries often fall into the "Heavy" category, directly impacting the average shipping cost per unit.

## 🛠️ Technical Workflow
- **Big Data Management (Excel):** Handled large-scale data processing using advanced Pivot Tables to summarize monthly parcel counts, average weights, and total costs.
- **Visual Business Intelligence (Tableau):** Developed a multi-page interactive dashboard to visualize the flow of goods from source to destination.
- **KPI Monitoring:** Tracked critical metrics like **Delivery Success Rate**, **Return Ratio**, and **In-Transit Volume**.

## 🔍 Key Insights & Features
- **Route Optimization:** Identified top-performing district pairs (e.g., Erode to Chennai) based on booking frequency and revenue.
- **Status Analysis:** Detailed breakdown of parcel lifecycles: Delivered, In-Transit, Cancelled, Pending, and Returned.
- **Product Segmentation:** Analyzed the distribution of parcel types—Medical, Electronics, Clothing, and Documents—and their associated shipping costs.
- **Time-Series Trends:** Visualized monthly fluctuations in booking volume to identify peak logistics seasons.

## 📈 Dashboard Highlights
- **Geographic Logistics Map:** Visualizing "From" and "To" district density.
- **Operational Health:** Real-time tracking of delivery status.
- **Financial Summary:** Total cost analysis by month and year (2024–2025).

## 📂 Repository Contents
- `Tamil_Nadu_Parcel_Service_Data.csv`: The core logistics dataset.
- `Parcel_Service_Analysis.twbx`: Interactive Tableau Workbook.
- `Logistics_Pivot_Summaries.xlsx`: Detailed Excel analysis and Pivot Tables.

## 📂 How to View
Download the Tableau file (.twbx) from this repository.
Open it using Tableau Public Desktop (free tool) 
[https://public.tableau.com/views/ParcelServiceAnalysis_17751145485040/OverallAnalysisDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link]
