# Topic-segmentation

Environment: Python 3	     
Technologies: sklearn, nltk, keras.              
Techniques: Vectorization, Tokenization, Stemming.

Data: consists of 2225 articles from bbc news website belonging to categories- business, sports, politics etc. from 2004-2005

The news articles are stored in .txt files in different directories pertaining to various news categories. The file 
topic_segment-dataset_preparation.ipynb extracts the articles from these .txt files and stores them in a dataframe which is then pickled(stored) in a file. This file is then imported in topic_segmentation_engine.ipynb and the dataframe is extracted for the purpose of modelling and training. 

Pre-processed the data and trained a classifier on it using multilayer LSTM for predicting the category of the news content.
Achieved accuracy of 90 percent on classification, using the multi-class confusion matrix.
