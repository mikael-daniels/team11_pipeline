# team11_pipeline
This repository contains two types of files:
1. python pipeline notebook
2. SQL express database backup file

# ETL pipeline notebook
- Extraction.ipynb extracts twitter data using tweepy.
- Transforming.ipynb extracts the twitter data and transforms the data into a pandas dataframe.
- Loading.ipynb extracts, transforms twitter data and then loads the data into a new table in a database.

# SQL express backup file
- Gather Eskom Cleaned Columns.bak is a back up file with existing tables where the extracted tweets will be loaded into.

# Setup
- download a notebook.
- open the jupyter notebook in jupyter or google colaboratory.
- restore .bak file to local SQL express server
- run the notebook

# Modules required to be installed:
- tweepy
- pandas
- numpy
