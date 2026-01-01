# Procurement SQL Analysis

## Overview
This project analyzes procurement and supplier performance data using SQL to derive spend, compliance, quality, and negotiation insights relevant to strategic sourcing and supply chain decision-making.

## Dataset
- Publicly available Procurement KPI dataset (777 purchase order records)
- Source: Kaggle (dataset not uploaded due to licensing)
- Data includes supplier, item category, pricing, quantity, compliance, and quality metrics

## Objectives
- Identify top suppliers by total spend
- Analyze procurement compliance distribution
- Evaluate supplier negotiation effectiveness
- Assess quality risk using defective unit metrics

## Tools & Technologies
- Python (Pandas)
- SQLite
- SQL (aggregations, joins, calculated fields)
- Jupyter Notebook

## Key Analyses Performed
- Supplier spend calculated using `quantity × negotiated_price`
- Compliance rate analysis across procurement orders
- Negotiation savings computed using unit vs negotiated price
- Supplier quality assessment using average defective units

## Key Results
- Analyzed 777 procurement records
- Identified top suppliers contributing highest spend
- Quantified negotiation savings by supplier
- Evaluated compliance and defect trends across suppliers

## Repository Structure
procurement-sql-analysis/
│
├── notebooks/
│ └── supplier_spend_analysis_sql.ipynb
├── sql/
│ └── queries.sql
├── outputs/
│ └── kaggle_procurement_supplier_spend.csv
└── README.md


## How to Run
1. Clone this repository
2. Download the dataset from Kaggle
3. Place the CSV in the project directory
4. Run the Jupyter notebook to recreate the analysis

## Notes
This project mirrors real-world procurement analytics work performed in enterprise
supply chain and sourcing teams.
