## Hi, I'm Sumaksharika 👋

👨‍💻 **Senior Data Engineer | 10+ years of experience**

I design and build scalable data platforms, distributed processing applications, cloud data lakes and enterprise ETL/ELT pipelines on AWS, Azure and Snowflake, across banking, healthcare, insurance, utilities and telecom.

💼 [LinkedIn](https://linkedin.com/in/sumaksharika)

### 🛠️ Tech stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?logo=apachespark&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/Bash%20%2F%20Shell-4EAA25?logo=gnubash&logoColor=white)

**Big data & streaming**
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?logo=apachespark&logoColor=white)
![Hadoop](https://img.shields.io/badge/Hadoop%20%2F%20HDFS-66CCFF?logo=apachehadoop&logoColor=black)
![Hive](https://img.shields.io/badge/Hive-FDEE21?logo=apachehive&logoColor=black)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?logo=apachekafka&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?logo=databricks&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4)

**Cloud**
- **AWS:** S3 · Glue & Glue Workflows · EMR · Lambda · Redshift · Step Functions · IAM · KMS
- **Azure:** Databricks · Data Factory · ADLS Gen2 · Azure SQL · Key Vault · Monitor & Log Analytics

**Warehousing & orchestration**
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?logo=snowflake&logoColor=white)
![Amazon Redshift](https://img.shields.io/badge/Amazon%20Redshift-8C4FFF)
![dbt](https://img.shields.io/badge/dbt-FF694B?logo=dbt&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?logo=apacheairflow&logoColor=white)
![Step Functions](https://img.shields.io/badge/AWS%20Step%20Functions-E7157B)
![Azure Data Factory](https://img.shields.io/badge/Azure%20Data%20Factory-0078D4)

**DevOps & CI/CD**
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?logo=jenkins&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white)

**BI & apps**
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?logo=tableau&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)

### 🧭 What I work on

- **Lakehouse & modeling:** Medallion architecture (Bronze/Silver/Gold), data lakes and warehouses, dimensional modeling, star schemas, SCD Type 1 & 2
- **ETL/ELT & integration:** batch, incremental and CDC pipelines; REST API and SFTP sources; CSV, JSON and Parquet; source-to-target mapping; validation and reconciliation
- **Performance tuning:** Spark partitioning, broadcast joins, caching, shuffle optimization, predicate pushdown, Delta OPTIMIZE and Z-ordering, Redshift and Snowflake tuning
- **Governance & security:** data-quality frameworks, profiling, schema validation, lineage, metadata management, RBAC, PII/PHI protection, encryption
- **Delivery:** CI/CD, unit testing, code reviews, release management, production support and root-cause analysis, Agile/Scrum

### 🚀 Data engineering pipelines

Each one runs end to end on synthetic data, with tests and CI.

| Project | What it does | Stack | CI |
|---|---|---|---|
| [Azure Lakehouse (Banking)](https://github.com/sumaksharikaa/azure-lakehouse-medallion-banking) | Metadata-driven Bronze/Silver/Gold lakehouse: incremental loads, SCD Type 2, data-quality gates | PySpark · Delta Lake · ADF | ![CI](https://github.com/sumaksharikaa/azure-lakehouse-medallion-banking/actions/workflows/ci.yml/badge.svg) |
| [AWS Healthcare Claims](https://github.com/sumaksharikaa/aws-healthcare-claims-pipeline) | Claims pipeline with PHI tokenization, Redshift loads and Step Functions orchestration | AWS Glue · Redshift · Terraform | ![CI](https://github.com/sumaksharikaa/aws-healthcare-claims-pipeline/actions/workflows/ci.yml/badge.svg) |
| [Snowflake Insurance Warehouse](https://github.com/sumaksharikaa/snowflake-dbt-insurance-warehouse) | P&C insurance warehouse: earned premium, loss ratios, snapshots, incremental models | dbt · Snowflake | ![CI](https://github.com/sumaksharikaa/snowflake-dbt-insurance-warehouse/actions/workflows/ci.yml/badge.svg) |
| [Smart-Meter Pipeline (Utilities)](https://github.com/sumaksharikaa/smart-meter-airflow-pipeline) | Daily meter-data pipeline: file controls, validation and gap-filling, outage reliability scores, write-audit-publish | Airflow 3 · PySpark · Hive | ![CI](https://github.com/sumaksharikaa/smart-meter-airflow-pipeline/actions/workflows/ci.yml/badge.svg) |
| [Telecom Kafka Streaming](https://github.com/sumaksharikaa/telecom-kafka-streaming-pipeline) | Network events streamed from Kafka: dead-letter queue, dedup, real-time cell KPIs, SCD2 subscriber changes, reconciliation | Kafka · Spark Streaming · Hive | ![CI](https://github.com/sumaksharikaa/telecom-kafka-streaming-pipeline/actions/workflows/ci.yml/badge.svg) |

### 🏥 Healthcare data engineering

ETL pipelines, warehouses and data-quality frameworks for pharmacy and claims data.

| Project | What it does | Stack |
|---|---|---|
| [Pharmacy Analytics dbt](https://github.com/sumaksharikaa/pharmacy-dbt-analytics) | Layered staging → intermediate → mart models with schema tests, singular tests and macros | dbt · Snowflake · SQL |
| [Specialty Pharmacy Claims](https://github.com/sumaksharikaa/sp-claims-analytics) | End-to-end claims ETL into a PostgreSQL warehouse, plus an executive dashboard | PostgreSQL · Python ETL · Streamlit |
| [Healthcare DQ & Governance](https://github.com/sumaksharikaa/healthcare-dq-governance) | Configurable data-quality rules engine with audit trail and downstream impact | Python · PostgreSQL |
| [Drug Utilization & Formulary](https://github.com/sumaksharikaa/drug-utilization-analytics) | Drug utilization and formulary analytics with prior-authorization tracking | MySQL · Python ETL · Streamlit |
| [Pharmacy Supply Chain](https://github.com/sumaksharikaa/pharmacy-supply-chain) | Inventory, supplier performance, stockouts and reorder alerts | PostgreSQL · Python ETL · Streamlit |

### 📊 Analytics & ML projects

| Project | What it does | Stack |
|---|---|---|
| [Readmission Risk Predictor](https://github.com/sumaksharikaa/pharmacy-readmission-risk) | 30-day readmission model using the Charlson Comorbidity Index | XGBoost · MLflow |
| [Financial Risk Dashboard](https://github.com/sumaksharikaa/financial-risk-dashboard) | Credit-risk analysis of a $34B, 2.26M-loan portfolio · [live demo](https://financial-risk-dashboard-ovjmqv7edtxfdeczx8zctv.streamlit.app) | SQL · Python · Streamlit |
| [Earnings Call NLP](https://github.com/sumaksharikaa/earnings-call-nlp) | FinBERT sentiment on earnings-call transcripts · [live demo](https://earnings-call-nlp-hpvrwqwv6rrtxknzwt2seb.streamlit.app) | Transformers · Streamlit |

### 📫 Open to

Senior Data Engineer roles in banking, healthcare, insurance and financial services.
