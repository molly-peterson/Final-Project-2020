** Taken from Tutorial Readme **
# Survival Analysis for Deep Learning

This is a [tutorial on survival analysis](https://k-d-w.org/blog/2019/07/survival-analysis-for-deep-learning/), also referred to as time-to-event analysis or reliability analysis. You will learn how to train a convolutional neural network to predict time to a (generated) event from MNIST images, using a loss function specific to survival analysis.

## Getting started

The easiest way to run this notebook is [Google Colaboratory](https://colab.research.google.com/github/sebp/survival-cnn-estimator/blob/master/tutorial.ipynb). If you want to run this notebook locally, you have to make sure the following dependencies are installed:

- [numpy](https://www.numpy.org/)
- [matplotlib](https://matplotlib.org/)
- [pandas](https://pandas.pydata.org/)
- [scikit-survival](https://github.com/sebp/scikit-survival/)
- [tensorflow](https://www.tensorflow.org/)

** Added to Readme **

tensorflow-gpu may also be installed in place of tensorflow. This code include logging so make sure that the version of tensorflow
that is downloaded is not the most recent. I used 1.14.0 and that worked. Make sure that the dependent modules are still compatible
with tensorflow if you are reverting back to an older version for this. 

Some code has been added to check to make sure GPU is available if you would prefer to use it over CPU.