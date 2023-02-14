# Document Analysis using GPT-3
This repository provides a set of examples for performing document analysis using OpenAI's GPT-3 language model. They are: 

* Data Exploration - Explore data used in this repo. 
* Get Embeddings - Generate embeddings from documents using GPT-3.
* Classify Documents - Use GPT-3 to classify documents into different categories.
* Summarize Documents - Automatically generate summaries of documents using GPT-3.
* Extract Key Information - Identify key information in documents using GPT-3.
* Extract Key Words - Extract important words from documents using GPT-3.

# BBC News Articles Analysis
This project is a data analysis of the BBC news dataset. The goal of this project is to explore the data, classify documents into categories, summarize documents, extract key information from documents and extract keywords from documents. 

## Dataset
The dataset used in this project is the [BBC News Archive](https://www.kaggle.com/datasets/hgultekin/bbcnewsarchive) available from [kaggle](www.kaggle.com). It contains 2225 articles from the BBC news website with 5 different categories: business, entertainment, politics, sport and tech. Each article has a category, filename, title and text.

## Notebooks
This project consists of five notebooks that perform the following tasks:

1. [00-explore-data.ipynb](./notebooks/00-explore-data.ipynb) - This notebook explores the data by looking at the distribution of classes, number of words per document, etc.
2. [01-get-embeddings.ipynb](./notebooks/01-get-embeddings.ipynb) - This notebook uses pre-trained word embeddings to create vector representations for each document.
3. [02-classify-documents.ipynb](./notebooks/02-classify-documents.ipynb) - This notebook builds classification models using Random Forest and XGBoost to predict the class of each document.
4. [03-summarize-documents.ipynb](./notebooks/03-summarize-documents.ipynb) - This notebook uses GPT-3 to generate summaries for each document.
5. [04-extract-key-information.ipynb](./notebooks/04-extract-key-information.ipynb) - This notebook extracts key information from each document such as people, organizations, locations, etc.
6. [05-extract-key-words.ipynb](./notebooks/05-extract-key-words.ipynb) - This notebook extracts important keywords from each document.

## Output
The output of this project is stored in the `output` directory. It contains the following files:

* [predictions.csv](./output/predictions.csv) - Predicted classes for each document
* [summaries.csv](./output/summaries.csv) - Generated summaries for each document
* [key_info.csv](./output/key_info.csv) - Extracted key information from each document
* [keywords.csv](./output/keywords.csv) - Extracted keywords from each document
* `models/rf.pkl` - Trained Random Forest model
* `models/xgb.pkl` - Trained XGBoost model

*Note: This README.md is co-authored with `text-davinci-003`.*