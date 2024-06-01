# Real Time Stock Market Analytics

## Introduction 
This project focuses on real-time stock market analytics powered by Kafka. We leverage Kafka's streaming capabilities to ingest, process, and analyze stock market data in real-time. Additionally, we utilize Amazon Web Services (AWS) for deploying and managing various components of the data pipeline.

## Technology Used
- **Programming Language**: Python
- **Amazon Web Service (AWS)**:
  1. **S3**: For storing raw and processed data.
  2. **Athena**: For querying data stored in S3 using SQL.
  3. **EC2**: For hosting applications and services.
- **Apache Kafka**: For building real-time streaming data pipelines and processing stock market data.

## Project Overview
1. **Data Collection**: The stock market data is collected from Kaggle, a platform for data science and machine learning enthusiasts.
2. **Data Processing**: Kafka consumers will process the incoming data streams, perform transformations, and store the processed data in S3.
3. **Data Analysis**: Processed data will be queried using Athena, enabling real-time analysis and visualization of stock market trends.
4. **Infrastructure**: AWS services such as S3, EC2, Kafka will be used to deploy and manage the project infrastructure.

