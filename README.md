# 📊 DataPilot AI — Automated Local-First Data Analytics Workspace

**From Raw Data to Smart Decisions | من البيانات الخام إلى قرارات ذكية**  
*Engineered by **Mohamed El-Khatib (محمد الخطيب)** — Data Analyst & Database Designer*

🔗 **Live Demo:** [Launch DataPilot AI](https://ma01121497497-ship-it.github.io/datapilot-ai/)

---

## 🚀 Overview
**DataPilot AI** is a zero-backend, privacy-first web application that automates the end-to-end data analysis workflow directly inside the browser. All file parsing, statistical calculations, SQL queries, and visualizations run 100% locally on the client's device without uploading sensitive data to any external server.

## ✨ Key Features (12-Stage Pipeline)
1. **Multi-Format Ingestion:** Drag-and-drop support for CSV, TSV, JSON, and Excel (`.xlsx` / `.xls`), plus raw text pasting and built-in sample datasets.
2. **Automated Data Profiling:** Instant schema detection, data type inference, cardinality, and summary statistics.
3. **Data Quality Audit:** Weighted quality scoring (Completeness, Uniqueness, Validity) with column-level missing value diagnostics.
4. **Non-Destructive Cleaning Studio:** Deduplication, missing value imputation (Mean/Median/Mode/Fixed), IQR outlier removal, and reproducible recipe logging.
5. **Data Transformation:** Group-by aggregations, safe arithmetic computed columns, sorting, and filtering.
6. **Built-in SQL Console:** Query active datasets directly using SQL (`SELECT`, `WHERE`, `GROUP BY`, `ORDER BY`) and promote query results into working tables.
7. **Exploratory Data Analysis (EDA):** Histograms, frequency distributions, scatter plots with Pearson $r$, and correlation heatmaps.
8. **Live KPI Builder:** Custom and auto-generated KPIs with group-by breakdowns.
9. **Interactive Visualizations & Dashboard:** Dependency-free HTML5 Canvas charts (Bar, Line, Pie, Scatter, Histogram) pinned to a live executive dashboard.
10. **Automated Insights & Reporting:** Heuristic anomaly/trend detection and one-click exportable HTML executive reports.

## 🛠️ Tech Stack
- **Core:** Vanilla JavaScript (ES6+), HTML5 Canvas, CSS3 (Custom Navy, Sky Blue & Gold Design System)
- **Local Persistence:** `IndexedDB` (Dataset Library) & `localStorage` (Session State)
- **Spreadsheet Engine:** SheetJS (`xlsx`) for client-side Excel parsing
