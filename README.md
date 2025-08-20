# Assignment_1

# 🏏 Cricket Match Data Analysis (Python + SQL + Power BI)

## 📌 Project Overview
This project demonstrates a **complete data pipeline** for cricket match analytics, starting from raw JSON data all the way to interactive dashboards in **Power BI**.  
It combines **Python, MySQL, SQL analysis, Power BI, and visualization libraries (Matplotlib/Seaborn)** to deliver actionable cricket insights.

---

## 🔑 Key Steps in the Project

### 1️⃣ Data Extraction & Processing
- Extracted **raw match data from JSON format**.  
- Used **Python (Pandas)** to read the JSON files and transform them into structured DataFrames.  

### 2️⃣ Database Management
- Designed and uploaded the cleaned data into a **MySQL database**.  
- Created normalized tables for batting, bowling, matches, etc.

### 3️⃣ SQL Analysis
- Wrote **20 SQL queries** to analyze cricket matches, including:  
  - Matches played against India by team  
  - India’s total wins and win percentage  
  - Venue-wise performance  
  - Player-wise runs and wickets  
  - Format-based (Test, ODI, T20) analysis  

### 4️⃣ Python Visualizations
- For selected SQL queries, visualized results in **Matplotlib** and **Seaborn**.  
- Exported charts (e.g., bar plots, line graphs, pie charts) and integrated them into **Power BI** for hybrid reporting.

### 5️⃣ Power BI Dashboard
- Imported SQL query results + Python charts into Power BI.  
- Created interactive dashboards including:  
  - **Bubble Chart** – India’s wins vs matches played by opponent  
  - **Pie Chart** – Distribution of wins by format (Test, ODI, T20)  
  - **Table** – Venue-wise win percentage  
  - Embedded Matplotlib/Seaborn charts alongside Power BI visuals  

---

### Project Structure

├── data/
│   └── raw_json/         # Cricsheet match files
├── scripts/
│   ├── scraper.py        # Downloads JSON files
│   ├── parser.py         # Extracts player/match info
│   └── db_loader.py      # Loads data into SQL
├── notebooks/
│   └── eda.ipynb         # Exploratory analysis
├── dashboards/
│   └── powerbi_report.pbix
└── README.md




## ⚙️ Tools & Technologies
- **Python** → Data extraction, cleaning, MySQL load  
- **Pandas** → Data manipulation  
- **MySQL** → Database & SQL queries  
- **SQL** → Analytical queries (20+)  
- **Matplotlib & Seaborn** → Visualizations  
- **Power BI** → Dashboards & reporting  

---

## 📥 How to Use
1. Clone this repository  
   ```bash
   git clone https://github.com/ramyaramadass27/cricket-analysis-project.git

2. Install dependencies

pip install -r requirements.txt


3. Load the data_processing.py script to populate MySQL with cricket data.


4. Run queries from cricket_queries.sql to reproduce insights.


5. Open Cricket_Analysis.pbix in Power BI Desktop to explore the dashboard.




---
📊 Key Insights
- Top run-scorers across seasons
- Strike rate vs match outcome
- Team performance trends
- Venue-based win patterns
📎 Data Source
All match data is sourced from Cricsheet, a free repository of structured cricket data.
🙋‍♀️ Author
Ramya

