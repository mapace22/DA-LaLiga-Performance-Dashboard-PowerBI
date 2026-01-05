# DA-LaLiga Performance Dashboard | Data Science Specialist

## 📌 Project Overview
As a Data Analyst for RiseData, I developed this interactive dashboard to provide La Liga with a competitive advantage through data-driven storytelling. This project (DA-Series) processes player statistics from the 2020-2021 season to explore key performance metrics.

## ⚙️ ETL Process (Extract, Transform, Load)
Using Power Query, I performed several data transformation steps:
- **Data Cleaning**: Standardized club names and handled null values in performance columns.
- **Feature Engineering**: Created a conditional `Age_Range` column (<=20, 21-25, 26-30, >30) for population segmentation.
- **Data Typing**: Standardized formats for ages, minutes, goals, and assists.

## 📊 DAX Measures & Analytics
I implemented a dedicated measures table (`Medidas_LaLiga`) using DAX to centralize business logic:
- `Total_Goals`: Aggregate sum of all goals scored.
- `Average_Assists`: Mean assists per player.
- `Average_Minutes`: Mean playing time per team.

## 📈 Visualizations
The dashboard features multiple perspectives:
- Team Performance (Bar Charts)
- Demographics (Pie Charts)
- Correlation Analysis (Scatter Plots)
- Efficiency Heatmap (Goals vs. Assists)

## 📂 Repository Structure
- `/report`: `la_liga.pbix` (Full Report)
- `/data`: `LaLiga_Mod1y3.csv` (Source Data)
- `README.md`
- `.gitignore`

## 🚀 Skills Demonstrated
- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query (M Language)**
- **Data Storytelling**
