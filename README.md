### Text Classification in Python using the 20 newsgroup dataset.
"20 newsgroups" dataset - Text Classification using Python. 

### Dataset

For dataset I used the famous "20 Newsgroups" dataset.

The data set is a collection of approximately 20,000 newsgroup documents, partitioned (nearly) evenly across 20 different newsgroups.
I've included the dataset in the repo, located at `20_newsgroups\` directory.

You can find the dataset freely [here](http://archive.ics.uci.edu/ml/datasets/Twenty+Newsgroups). 

### The code

The code is pretty straight forward and well documented. 
The preprocessing of the documents and the implementation of classifiers have been done from scratch and then the results have been compared to inbuilt sklearn's classifiers. 
The code has been arranged in form of IPython Notebooks, each notebook corresponds to a particular "classifier" or "technique" used for classifying the dataset.

### Requirements

* python 2.7 or above
* python modules:

  * scikit-learn
  * numpy
  * matplotlib
  
### Experiments

For each experiment we use a "feature vector", a "classifier" and a train-test splitting strategy.

#### Experiment 1: BOW - NB - 25% test

In this experiment we use a Bag Of Words (**BOW**) representation of each document containing Term Frequency. And also a Multinomial Naive Bayes (**NB**) classifier.

#### Experiment 12: TF-IDF - NB - 25% test
_Ongoing_
