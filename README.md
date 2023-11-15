# Twitter Sentiment Analysis with Python

Welcome to the Twitter Sentiment Analysis project, implemented as a capstone project for the General Assembly Data Science Immersive course. This project focuses on analyzing sentiments expressed in tweets using various techniques, with a primary implementation based on Convolutional Neural Network (CNN) using Word2Vec.

## Overview

This project is aimed at understanding and categorizing the sentiment behind tweets posted on Twitter. Sentiment analysis involves determining whether a piece of text expresses positive, negative, or neutral sentiments. In this repository, you will find a Jupyter Notebook containing the implementation details and analysis of the Twitter Sentiment Analysis project.

## Implementation Details

### Convolutional Neural Network with Word2Vec

The primary approach used in this project is a Convolutional Neural Network (CNN) with Word2Vec embeddings. Word2Vec is employed to represent words in a continuous vector space, capturing semantic relationships between words. The CNN architecture helps in learning patterns and features from these word embeddings to make sentiment predictions.

To run the CNN with Word2Vec implementation, make sure to have the following prerequisites installed:

- [TensorFlow](https://github.com/tensorflow/tensorflow)
- [Keras](https://github.com/keras-team/keras)
- [Gensim 3.2.0](https://github.com/RaRe-Technologies/gensim)

You can install these dependencies using the following commands:

```bash
pip install tensorflow
pip install keras
pip install gensim==3.2.0
