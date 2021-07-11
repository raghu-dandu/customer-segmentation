# Customer Segmentation or Clustering

## Table of contents
* [Project info](#project-info)
* [Technologies](#technologies)
* [Dataset](#dataset)
* [Setup](#setup)

## Project info
 Customer segmentation helps the Telcos to segment the customers based on interests and opinion about products, services and new launches. This will greatly helps the Telcos to plan their campaigns and improvement to services.

 This project uses customer tweets labelled with sentiments(Positive / Negative / Neutral) (please see sentiment-analysis repository), and segment / cluster the customers based on tweets into n clusters.
 
 Predicts segment / cluster for new customers based on tweets
	
## Technologies
* Python 3.x
* Natural Language processing (NLP): Statistical NLP, spaCY, gensim
* Machine Learning: LDA, kNN classifier
* AWS EC2 (c3.4xlarge)

## Dataset
* Twitter Dataset from 5 Telcos
* Size: 1.5 GB ( 300 MB approx from each Telco)
* Tweets: 5 million (1 million from each Telco)
* Dataset folder has only sample of data (100K tweets) 


## Setup
The project originally run in High-end cloud (AWS EC2 c3.4xlarge) due to high volume of data.
The project can be run in stand-alone machine with sample data from orginal datasets.
```
-> copy Code and Dataset folders onto PC or Cloud Compute machines
-> Open ipython (Jupyter) notebook.
-> Upload .ipynb files
-> Changes the file path as per the OS and run all cells.

```
