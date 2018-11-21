# Blight-Buildings-Predictive-Analytics

In this project, I have built a model to predict blight risk buildings in advance in Detroit city.

Datasets:
========
- detroit-blight-violations.csv : Each record is a blight violation incident. 
- detroit-demolition-permits.tsv: Each record represents a permit for a demolition. 
- detroit-311.csv: Each record represents a 311 call, typically a complaint 
- detroit-crime.csv: Each record represents a criminial incident.

The above public datasets are taken from http://data.detroitmi.gov. For each incident type, the location is included as a latitude,
longitude pair and various timestamps are included.

Project is divided into the following sections:
==========================================
1) Preprocessing the data (after obtaining raw data)
2) Clustering the data (clustering incidents under buildings. So each building can have multiple incidents associated with it)
3) Feature Engineering (Generating Features for the data)
4) Applying machine-learning models

To Do:
=====
- Visualize the raw data through more graphs and draw inferences. 
- Try different models like random forests and compare the results. 
- Include more meaningful features in the data
