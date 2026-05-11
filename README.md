# NorthStar Operational Analytics & NoSQL MigrationStudent
Name: Sneha Parapurath | Student ID: 32146917 
## Project Overview:
This repository contains a full-stack analytical pipeline designed to resolve operational fragmentation and "Relational Rigidity" at NorthStar Logistics . The project transitions from initial relational diagnostics in SQL and R to deep statistical profiling in Python, concluding with a scalable migration to a cloud-native NoSQL (MongoDB Atlas) architecture.  
## Repository Structure
/SQL_R_Diagnostics: R script utilizing sqldf for initial data unification and service-level failure analysis .  
/Python_Performance_Audit: Documentation of the statistical profiling, correlation heatmaps, and geographic latency audits.  
/MongoDB_Atlas_Migration: Technical implementation of NoSQL document modeling, atomic CRUD operations, and index optimization.  
/data: Centralized storage for nine operational datasets, serving as the "Single Source of Truth".  
## Setup & Reproducibility
Data Ingestion: All notebooks are configured to pull raw CSV data directly from the /data folder in this repository to ensure consistent results.  
## Environment:
R: Optimized for Google Colab with sqldf and tidyverse.  
Python: Requires pandas, seaborn, and matplotlib.  
MongoDB: Requires pymongo and a valid MongoDB Atlas connection string.  
Execution: Scripts should be run in sequence (R -> Python -> MongoDB) to follow the logical diagnostic progression. 
