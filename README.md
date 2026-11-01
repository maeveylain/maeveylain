# Hi, I'm Maeve Ylain Sean 👋

**Data Engineer** · Databricks Certified · 🏆 Best Capstone, FTW 2026 · Laguna, Philippines

I moved from chemical engineering, where I did semiconductor yield analysis, into data engineering. Yield work taught me that a decision is only as good as the data behind it. Now, I build the systems that produce that data, from raw ingestion to tested, analytics-ready tables.

- 🏅 **Databricks Certified Data Engineer Associate** (2026)
- 🎓 **FTW Foundation x Accenture Data Engineering Scholar**, Jun–Oct 2026 
- ⚗️ Licensed Chemical Engineer · BS ChemEng, UP Los Baños

---

### 🛠️ Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=databricks&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)

**Platform & Pipelines**
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD4?style=flat&logo=delta&logoColor=white)
![Unity Catalog](https://img.shields.io/badge/Unity_Catalog-1B3139?style=flat&logo=databricks&logoColor=white)

**Testing, CI/CD & Tools**
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)

**What I work with**
- Medallion architecture (Bronze → Silver → Gold)
- Dimensional modeling (star schema: facts & dimensions)
- Data quality gates & quarantine tables
- Databricks Jobs & Asset Bundles (CI/CD to dev/prod)
- Databricks AI/BI (Lakeview) dashboards

---

### 🌟 Spotlight: ReachED – Education Access Intelligence 🏆
*Best Capstone, FTW Data Engineering 2026*

Helps Local School Boards in the Philippines see **which cities and municipalities need classrooms and teachers most**. The pipeline brings together 9 official DepEd, PSA and HDX sources, matches every public school to its PSGC code, and turns the result into a planning-priority list.

- End-to-end pipeline on Databricks: Bronze → Silver → Integration → Gold → Analytics
- A validation check after every layer, with results tracked on a data-quality dashboard
- Star-schema Gold layer (school, city/municipality, school year, enrollment, classroom and teacher capacity)
- CI with GitHub Actions + pytest; deployed with Databricks Asset Bundles
- **My role:** I built the geography backbone that lets the pipeline compare every Philippine city and municipality. I owned the PSGC reference and the school-to-PSGC crosswalk in Silver, integrated census population data, and delivered 3 Gold tables with validation gates, tests and source-to-Gold reconciliation. I also led the storytelling for our Best Capstone presentation.

🔗 [View the repository](https://github.com/reached-hq/edu-access-intelligence)

---

### 📂 Other Projects

| Project | What it does | Tech | My role |
|---|---|---|---|
| [NYC Mobility Pipeline](https://github.com/Lvzxc/nyc-mobility-pipeline) | Turns NYC taxi, taxi-zone and weather data (Parquet, CSV, open API) into an analytical data warehouse | Databricks, Delta Lake, Unity Catalog, SQL, Python | Built the Gold `fact_taxi_trip` table, fixed duplicate rows caused by hour-truncated timestamps, added surrogate keys from the date-time and location dimensions, and wrote its data quality checks |
| [Instacart Data Pipeline](https://github.com/killuazai/instacart-data-pipeline) | Medallion pipeline over 37M+ grocery-order records, from raw CSVs to a star schema and a business dashboard | Databricks SQL, Delta Lake, Unity Catalog, Lakeview | Wrote the business-question analytics (incl. products most often bought together) and built and documented the Lakeview insights dashboard |
| [OULAD Learning Analytics](https://github.com/Lvzxc/oulad-pipeline) | Warehouse and analytics on Open University learning data: student engagement, assessment performance and withdrawal | Databricks, Delta Lake, Unity Catalog, SQL, Python | Built the Silver `clean_courses` table and the Gold `dim_course` and `dim_assessment` tables with surrogate keys; wrote the activity-trends analysis by course-duration decile |
| [Chinook Data Pipeline](https://github.com/hyenalouise/chinook-data-pipeline) | Revenue, customer and pricing analytics for a digital music store, from raw CSVs to a 3-page dashboard | Databricks, SQL, Unity Catalog, Databricks Jobs | Wrote the pipeline's validation documentation (row counts, key checks, revenue reconciliation, layer by layer) |

---


### 📫 Let's connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maeveylainsean/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:myslumague@gmail.com)
