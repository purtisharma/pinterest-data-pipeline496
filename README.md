# pinterest-data-pipeline
# Pinterest Data Pipeline

## Table of Contents
- [Project Description](#project-description)
- [Installation Instructions](#installation-instructions)
- [Usage Instructions](#usage-instructions)
- [File Structure](#file-structure)
- [License Information](#license-information)
- [Tech Stack](#tech-stack)
- [What I've Learned](#what-ive-learned)

## Project Description
This project integrates AWS services with Apache Kafka, Spark, Airflow, and Databricks, using Python as the primary language. The aim is to build a robust data pipeline that involves setting up and configuring various components to handle data processing and scheduling. Key tasks include configuring AWS IAM roles, EC2 instances, S3 buckets, MSK Cluster, API Gateways, MWAA Scheduler, and Kinesis Data Streams; creating and managing Kafka topics; using Spark on Databricks for ETL processes; and orchestrating workflows with Airflow.

## Installation Instructions

### AWS Setup:
- Configure IAM roles, EC2 instances, S3 buckets, MSK Cluster, API Gateways, MWAA Scheduler, and Kinesis Data Streams.

### Kafka Setup:
- Create Kafka topics, configure producers and consumers, and set up a REST proxy.

### Databricks Setup:
- Host Spark on Databricks and set up notebooks with Python and PySpark.

### Airflow Setup:
- Create a DAG to schedule Databricks Notebooks.

## Usage Instructions

### Kafka:
- Use the provided Kafka topics to produce and consume data.

### Spark:
- Run ETL jobs on Databricks using PySpark.

### Airflow:
- Monitor and manage DAGs to schedule Databricks jobs.

## File Structure

