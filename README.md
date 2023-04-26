# Youtube Data Analysis Project 

## Overview

This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.


## Goals and success:

1. Data Ingestion — Build a mechanism to ingest data from different sources
2. ETL System — We are getting data in raw format, transforming this data into the proper format
3. Data lake — We will be getting data from multiple sources so we need centralized repo to store them
4. Scalability — As the size of our data increases, we need to make sure our system scales with it
5. Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS
6. Reporting — Build a dashboard to get answers to the question we asked earlier

## What all i can learn from this project:

1. To build a data lake from scratch using AWS S3 - joining Structured and Semi-Structured data
2. Lake House architecture design 
3. Data Lake vs Data Warehouse
4. Data lake design in layers, Partitioned for cost-performance - WORM model/Write Once read Many
5.AWS DATA catalog
6.ETL jobs in AWS Glue Spark Jobs
7.AWS SNS for alerting
8.SQL using AWS Athena and Spark SQL
9. learn to write scripts to ingest changes incrementally and schema evolution
10. BI dashboards in AWS quicksight

## Dataset Used

This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new
