# Customer 360 Project README

## Overview
The Customer 360 project aims to create a unified view of customer data by integrating, cleaning, and storing information from various sources. The project will utilize Python Pandas for data processing, an SQL database for initial storage and cleaning, MongoDB for the unified customer view, FastAPI for the backend API, Streamlit for the frontend interface, and Google Cloud Platform (GCP) for cloud deployment.

## Project Steps

### Step 1: Data Loading and Storage
- CSV data will be loaded into an SQL database using Python Pandas.
- Data cleaning and transformation may be performed directly in the SQL database.

### Step 2: Data Modeling and Cleaning
- SQL and Python Pandas will be used to further clean and preprocess the data.
- Data validation, filtering, and transformation will be applied to create a structured dataset.

### Step 3: Data Integration and MongoDB
- Cleaned data will be extracted from the SQL database.
- Data will be transformed into MongoDB documents and stored in a unified customer view.

### Step 4: Backend API (FastAPI)
- FastAPI will be used to create a backend API to interact with the MongoDB database.
- The API will provide endpoints to access and manipulate customer data.

### Step 5: Frontend Interface (Streamlit)
- Streamlit will be utilized to create an interactive frontend interface.
- Users will be able to visualize and explore the unified customer view through this interface.

### Step 6: Cloud Deployment (GCP)
- Google Cloud Platform (GCP) will be used to deploy the application to the cloud.
- Deployment may involve setting up virtual machines, containerization, and related services.


## Project Structure
- `data_loading`: Contains scripts and instructions for loading CSV data into SQL database.
- `data_cleaning`: Contains scripts and instructions for further data cleaning and preprocessing.
- `data_integration`: Contains scripts and instructions for integrating data into MongoDB.
- `backend`: Contains FastAPI backend code and instructions.
- `frontend`: Contains Streamlit frontend code and instructions.
- `cloud_deployment`: Contains deployment guide for Google Cloud Platform.


## Contact
For any questions or inquiries, please contact gselewan@gmail.com