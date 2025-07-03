# Azure-End-to-End-Data-Engineering-Project-with-CI-CD-Paris-2024-Olympics

[![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)](https://azure.microsoft.com/)
[![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)](https://databricks.com/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org/)
[![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white)](https://spark.apache.org/)

## 🎯 Project Overview

This comprehensive **Azure Data Engineering** project demonstrates the implementation of a modern, scalable data pipeline using the **Paris 2024 Olympics dataset**. The project showcases industry best practices including **CI/CD with Azure DevOps**, **Medallion Architecture**, and **Delta Live Tables** for building robust, enterprise-grade data solutions.

### 🏗️ Architecture Highlights

- **Medallion Architecture**: Bronze → Silver → Gold data layers for progressive data refinement
- **Azure DevOps CI/CD**: Complete continuous integration and deployment pipeline
- **Delta Live Tables**: Declarative ETL framework for reliable data processing
- **Unity Catalog**: Centralized data governance and access control
- **PySpark**: Big data transformations with Python-based Spark operations
- **Real-time Analytics**: Interactive dashboards with Power BI integration

## 📋 Data Architecture
![DataArch](https://github.com/shivaaganesh3/Azure-End-to-End-Data-Engineering-Project-with-CI-CD-Paris-2024-Olympics/blob/e52439e1902ef409b25deb03bc72b47ff460e03b/architecture_design.png)
## 🛠️ Technology Stack

| Layer | Technology | Purpose |
|-------|------------|---------|
| **Data Sources** | GitHub API, CSV Files | Raw data ingestion from multiple sources |
| **Data Ingestion** | Azure Data Factory, Autoloader | Automated ETL pipelines with CI/CD |
| **Data Storage** | Azure Data Lake Gen2, Delta Lake | Scalable, cost-effective storage with ACID transactions |
| **Data Transformation** | Azure Databricks, PySpark | Big data processing and transformation |
| **Data Processing** | Delta Live Tables, Spark Streaming | Declarative ETL with real-time capabilities |
| **Data Governance** | Unity Catalog, Azure AD | Centralized security and data lineage |
| **DevOps** | Azure DevOps, Git, ARM Templates | CI/CD automation and infrastructure as code |
| **Analytics** | Power BI, SQL Warehousing | Interactive dashboards and reporting |

## 📊 Dataset Information

**Paris 2024 Olympics Summer Games Dataset**
- **Athletes**: Comprehensive athlete profiles with demographics and performance data
- **Events**: Olympic events, categories, and competition details  
- **Coaches**: Coaching staff information and athlete relationships
- **NOCs**: National Olympic Committees and geographical data

## 🏛️ Medallion Architecture Implementation

### 🥉 Bronze Layer (Raw Data)
- **Purpose**: Ingestion of raw data from source systems
- **Format**: Parquet files for optimized storage and performance
- **Technology**: Spark Structured Streaming with Autoloader
- **Features**: 
  - Exactly-once semantics
  - Schema evolution support
  - Automatic file discovery and processing

### 🥈 Silver Layer (Cleaned Data)
- **Purpose**: Data cleansing, validation, and standardization
- **Technology**: PySpark with Python OOP principles
- **Transformations**:
  - Data type conversions and normalization
  - Missing value handling and data quality checks
  - Business rule implementation
  - Unity Catalog function integration

### 🥇 Gold Layer (Business-Ready Data)
- **Purpose**: Curated, analytics-ready datasets
- **Technology**: Delta Live Tables with declarative SQL/Python
- **Features**:
  - Star schema dimensional modeling
  - Slowly Changing Dimensions (SCD Type 1 & 2)
  - Data quality expectations and constraints
  - Optimized for analytical workloads

## 🔄 CI/CD Pipeline Flow

### Development Workflow
1. **Feature Branch Creation**: Developers create feature branches from main
2. **Development**: Code changes in isolated development environment
3. **Pull Request**: Code review and automated testing
4. **Merge to Main**: Integration into main collaboration branch
5. **Automated Deployment**: ARM template generation and deployment

### Azure DevOps Integration
- **Version Control**: Git-based source control with branching strategy
- **Automated Publishing**: ARM template generation from Data Factory
- **Environment Promotion**: Dev → UAT → Production deployment
- **Release Pipelines**: Automated deployment with approval gates

## 🚀 Key Features

### 📈 Real-Time Data Processing
- **Spark Structured Streaming**: Continuous data ingestion and processing
- **Change Data Capture (CDC)**: Real-time capture of data changes
- **Low-Latency Pipelines**: Near real-time analytics capabilities

### 🔍 Data Quality & Governance
- **Unity Catalog Integration**: Centralized data governance
- **Data Quality Checks**: Automated validation rules and constraints
- **Lineage Tracking**: End-to-end data lineage visualization
- **Access Control**: Fine-grained security with Azure AD integration

### 🎨 Dynamic & Parameterized Pipelines
- **Dynamic Notebooks**: Reusable, parameterized data processing logic
- **Workflow Orchestration**: Databricks workflows for complex dependencies
- **Error Handling**: Comprehensive error management and retry logic


