%md
# Banking Data Ingestion & Analysis Project

## Overview

This project demonstrates a metadata-driven approach for ingesting, transforming, and analyzing banking data using Databricks on AWS. The workflow is organized into three main notebooks:

- **01_ingestion.ipynb**: Metadata-driven ingestion of raw data files into Delta tables.
- **02_transformation.ipynb**: Data cleaning, normalization, and creation of silver tables.
- **03_kpi_analysis.ipynb**: Calculation of key performance indicators (KPIs) and advanced analytics.

## Deliverables

- `01_ingestion.ipynb`: Ingests JSON and CSV files from Unity Catalog Volumes into raw Delta tables.
- `02_transformation.ipynb`: Transforms raw tables into clean, analytics-ready silver tables.
- `03_kpi_analysis.ipynb`: Performs KPI calculations and creates views for business analysis.
- `metadata_config.json`: Metadata configuration file describing the ingested datasets.
- `README.md`: Project documentation and instructions.
- *(Optional)* Dashboard screenshots for visual insights.

## Setup Instructions

1. **Attach a Databricks cluster** (AWS, Spark 4.6+).
2. **Upload notebooks** to your workspace.
3. **Ensure data files** are available in `/Volumes/databricks_catalog/default/databricks_project_volume/`.
4. **Run notebooks in order**: Start with `01_ingestion.ipynb`, then `02_transformation.ipynb`, and finally `03_kpi_analysis.ipynb`.

## Usage

- Use the control table and metadata_config.json to manage and audit data ingestion.
- Query Delta tables and views for analytics and reporting.
- Review dashboard screenshots for visual summaries (if provided).

## Contact

For questions or support, please contact the project owner or your Databricks administrator.