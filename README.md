# databricks-delta-lake-pipeline
End-to-end data engineering pipeline using Medallion Architecture. Implementing Delta Lake for ACID compliance, schema enforcement, and time-travel capabilities within a Databricks environment.

## 🏗️ Architecture

This project follows the **Medallion Architecture**:


![High Level Architecture](Docu/architecture.png)

### 🥉 Bronze Layer
- Raw data ingestion  
- Schema inference and storage as Delta tables  

### 🥈 Silver Layer
- Data cleaning and standardization  
- Type casting and validation  

### 🥇 Gold Layer
- Dimensional Data Model (Business Transformation)
- Ready for BI and analysis  

---

## 🛠️ Technologies Used

- Databricks  
- Apache Spark  
- PySpark  
- Spark SQL  
- Delta Lake  
- Unity Catalog  


