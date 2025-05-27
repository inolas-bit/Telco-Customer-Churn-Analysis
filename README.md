#  Telco Customer Churn Analysis & Power BI Dashboard

A comprehensive end-to-end analytics project focused on customer churn behavior using Python for data processing and Power BI for interactive data visualization.


##  Project Objective

To identify key patterns and risk factors contributing to customer churn at a telecom company. This solution empowers business stakeholders to take proactive retention actions.


## 📂 Dataset

Source: [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
Final File Used: `cleaned_telco_churn.csv` (preprocessed with Python)



## Tools & Technologies

| Category            | Stack                                 |
|---------------------|----------------------------------------|
| Data Cleaning       | Python (Pandas, NumPy)                |
| EDA & Visualization | Seaborn, Matplotlib                   |
| BI Dashboard        | Power BI Desktop                      |
| File Format         | CSV, PBIX                             |



##  Power BI Dashboard Highlights

## Key Insights Visualized
- Churn Rate by:
  - Gender, Contract Type, Internet Service, Payment Method
- Monthly Churn Trend
- KPI Cards:
  - Total Customers
  - Churned Customers
  - Churn % by Contract & Tenure


## Tooltips Enriched With
- Monthly Charges
- Total Charges
- Tech Support Status
- Contract Type

###  Drill-Down Filters
- Gender
- Senior Citizen Status
- Internet Service Type
- Payment Method
  


##  Python Workflow Summary

- Data cleaning & transformation
- Missing value imputation
- Label & One-Hot Encoding
- Outlier detection
- Exploratory data analysis (EDA)
- Exported cleaned dataset for BI use



## 📁 Repository Structure

| Folder/File                  | Description                                  |
|-----------------------------|----------------------------------------------|
| `cleaned_telco_churn.csv"` | Cleaned dataset ready for Power BI         |
| `Telco Customer Churn Analysis-checkpoint.ipynb"`   | Python notebook for cleaning & EDA         |
| `Telco Customer Chrun insights Dsshbaord ` | Power BI dashboard file             |
| `README.md`                     | Project documentation                      |

---

## 💻 How to Run

1. Clone the repository:
   bash
   git clone https://github.com/inolas-bit/telco-churn-analytics.git
   cd telco-churn-analytics
