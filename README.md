# Stock Market Kafka Real-Time Data Engineering Project
Introduction

This project demonstrates an end-to-end data engineering pipeline that processes real-time stock market data using Apache Kafka. The system captures live stock data, stores it in Amazon S3, and processes it using AWS Glue and Athena for querying. The project focuses on the operational aspects of building scalable data pipelines and integrating real-time data streams with cloud services.
Architecture

The architecture of the pipeline is designed for real-time data processing, leveraging Apache Kafka for stream ingestion, AWS S3 for storage, and AWS Glue for data processing and cataloging. The data is then made accessible for analytics and querying via Amazon Athena.
Technologies Used

![Architecture](https://github.com/user-attachments/assets/dce2decc-2b5c-4e80-98cb-bb8ca350b823)

    Programming Language: Python
    Amazon Web Services (AWS):
        S3 (Simple Storage Service): For storing raw and processed data.
        Athena: For querying the data stored in S3 using SQL.
        Glue Crawler & Glue Catalog: For automated data cataloging and schema management.
        EC2: For hosting and running the pipeline components.
    Apache Kafka: For real-time data stream processing and ingestion.

Dataset

While the dataset can vary, the focus of this project is on the operational side of data engineering, particularly building the data pipeline for real-time streaming data. The project can be adapted to work with any publicly available stock market dataset or API.
