# NLP
I have started getting quite interesting in the concept of Natural Language Processing and tried to implement and understand this concept from a blog i read from towardsdatascience.com.
Sentiment Analysis is a common NLP task that Data Scientists need to perform. This is a straightforward guide to creating a barebones movie review classifier in Python.
For this analysis we’ll be using a dataset of 50,000 movie reviews taken from IMDb. The data was compiled by Andrew Maas and can be found here: IMDb Reviews.
The data is split evenly with 25k reviews intended for training and 25k for testing your classifier. Moreover, each set has 12.5k positive and 12.5k negative reviews.
IMDb lets users rate movies on a scale from 1 to 10. To label these reviews the curator of the data labeled anything with ≤ 4 stars as negative and anything with ≥ 7 stars as positive. Reviews with 5 or 6 stars were left out.

I have made the task of obtaining the dataset easy by unpacking and merging the files into two txt files (Train and Test) and have uploaded them by zipping them to my git.

Please check the .ipynb file as it has comments which give a explanation of what i have done.
