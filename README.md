# Ontario Bridge Infrastructure & Condition Analysis

### Python | SQL Server | ETL | Power BI | DAX

## Project Overview

An end-to-end Business Intelligence project analyzing Ontario bridge infrastructure and historical Bridge Condition Index (BCI) records.

The project demonstrates how raw government data can be transformed into a relational database and visualized through an interactive Power BI report to support infrastructure analysis.

## Dataset

**Source:** Ontario Open Data Portal — Bridge Conditions

- 5,053 bridge records
- 44,149 historical BCI records
- Historical observations covering 2000–2020
- Bridge attributes including highway, location, material, and condition scores

## Technologies Used

- **Python:** CSV processing and database automation
- **Pandas:** Data inspection and preparation
- **SQL Server:** Relational database storage and querying
- **pyodbc:** Python-to-SQL Server connectivity
- **SQL:** Joins, lookup tables, normalization, and UNPIVOT
- **Power BI:** Interactive reporting and geographic visualization
- **DAX:** Calculated measures and performance indicators

## Project Workflow

1. Extracted Ontario bridge data from CSV.
2. Loaded 5,053 records into a SQL Server staging table.
3. Created lookup tables for bridge materials and categories.
4. Organized bridge attributes into a master table.
5. Applied UNPIVOT to transform yearly BCI columns into 44,149 historical records.
6. Connected SQL Server to Power BI.
7. Built a relational data model and DAX measures.
8. Developed and published an interactive Power BI report.

## Dashboard Features

**Bridge Overview**
- Total Bridges KPI
- Total BCI Records KPI
- Average BCI KPI
- Historical BCI trend chart
- Bottom 10 highways by average recorded BCI
- Interactive

## Power BI Dashboard Screenshots

### Bridge Overview
![Bridge Overview](Screenshot%202026-10-20%20235949.png)

### Bridge Details
![Bridge Details](Screenshot%202026-10-21%20000045.png)
