# Data Warehouse and Analystics Project
This project demonstrates a comprehensive data warehousing and analytics solution from building a data warehouse to a generating actionable insights.

## 📖 Project Overview
This project involves:

* **Data Architecture:** Implementing a multi-hop (Medallion) structure.
* **ETL Pipelines:** Automated Extraction, Transformation, and Loading logic.
* **Data Modeling:** Designing a Star Schema with Fact and Dimension tables.
* **Quality Assurance:** Ensuring data integrity across all layers.

 ## Data Architecture
 The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers: Data Architecture

1- Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2- Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3- Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.


## 📂 Repository Structure
```bash
data-warehouse-project/
│
├── datasets/            # Raw datasets (ERP and CRM data)
├── docs/                # Architecture, ERDs, and Data Catalog
│   ├── etl.drawio       # ETL techniques & methods
│   ├── data_models.drawio # Star Schema (Fact/Dim) diagrams
│   └── data_catalog.md  # Metadata and field descriptions
├── scripts/             # SQL Transformation scripts
│   ├── bronze/          # Raw data loading scripts
│   ├── silver/          # Cleaning & normalization logic
│   └── gold/            # Final analytical model creation
├── tests/               # Data quality and integrity scripts
├── README.md            # Project documentation
└── requirements.txt     # Dependencies
```
## 🛠️ Tech Stack
    Database: Microsoft SQL Server
    Language: T-SQL (Transact-SQL)
    Modeling: Star Schema (Fact & Dimension)
    Design Tools: Draw.io (Architecture & Data Flow)

## 🛡️ License
This project is licensed under the MIT License. You are free to use, modify, and share this project with proper attribution.

---

## 🙏 Acknowledgements
This project was developed as part of the **Data Engineering Roadmap** by [Data with Baraa](https://www.youtube.com/@datawithbaraa). 
* Special thanks to Baraa for the architectural guidance and dataset resources.
* The implementation, SQL scripting, and documentation were performed by me as part of my learning journey.

## 🌟 About Me
Mohab Yousry Junior Data Engineer

Passionate about building robust data pipelines and turning raw data into business value.

LinkedIn | Portfolio
