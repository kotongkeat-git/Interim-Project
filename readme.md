# **Interim Project: HDB Resale Price Analysis**
## **First Python Assignment | Data Engineering & ETL Pipeline**

### **📌 Project Overview**
This project focuses on building a robust ETL (Extract, Transform, Load) pipeline to analyze Singapore's HDB Resale Flat prices. The objective is to move raw data from an external source (Kaggle) into a structured environment (PostgreSQL) for deeper analytical insights.

The analysis utilizes the Singapore Resale Flat Prices dataset (Jan-17 to Sep-25) to track market trends and pricing fluctuations over nearly a decade.

### **🚀 The ETL Workflow**
My primary contribution to this team project is the ETL notebook, which follows a strictly sequenced, step-by-step architecture:

#### **1. Extraction (E)**
Kaggle API Integration: Automated the retrieval of the latest dataset directly from Kaggle using Python.

Get Started with Kaggle's Public API
Refer https://www.kaggle.com/discussions/getting-started/524433

#### **2. Transformation (T)**
Data Cleaning: Handling missing values and ensuring data types (dates, floats, integers) are optimized for analysis.
               Processing address strings and flat types to prepare the data for geospatial mapping or predictive modeling.

#### **3. Loading (L)**
PostgreSQL Integration: Establishing a connection to a PostgreSQL database.

Schema Mapping: Loading the transformed Pandas DataFrames into structured SQL tables for team-wide access and SQL-based querying.

### **📖 Notebook Structure**
The notebook is designed with clarity and collaboration in mind. It is divided into logical sections:
Step-by-Step Processing: Each cell represents a specific stage in the pipeline to make debugging and peer-review easier for the project team.

### **📊 Basic Flow Diagram**
<img width="1274" height="991" alt="image" src="https://github.com/user-attachments/assets/3f390fe9-199e-47f2-a2a4-c2ad46f5f50f" />
