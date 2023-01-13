# Data-Warehouse
Data Engineer Project1

## Contents
1.[Introduction](#1-introduction)
2.[Dataset](#2-dataset)
3.[Structure](#3structure)

## 1. Introduction

A music streaming startup, Sparkify, has grown their user base and song database and **want to move their processes and data onto the cloud**. Their data resides in S3, in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.

In this project, I will:
- Build an ETL pipeline that extracts data from AWS S3, load data from S3 into staging tables on Redshift and  process data into analytics tables on Redshift.
- Design fact and dimension tables for the star schema optimized for analytics team to continue finding insights in what songs their users are listening to.
- Create an IAM Role that makes Redshift able to access S3 bucket and Redshift cluster using Python SDK

## 2. Dataset

I'll be working with two datasets that reside in S3:
- Song data: `s3://udacity-dend/song_data`
- Log data: `s3://udacity-dend/log_data`

## 3. Repo Structure
- 
