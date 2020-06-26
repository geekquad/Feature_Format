# Feature_Format


[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

A python dictionary can’t be read directly into an sklearn classification or regression algorithm; instead, it needs a numpy array or a list of lists (each element of the list (itself a list) is a data point, and the elements of the smaller list are the features of that point).

I’ve written some helper functions (featureFormat() and targetFeatureSplit()) that can take a list of feature names and the data dictionary, and return a numpy array.

Just pip install it. 