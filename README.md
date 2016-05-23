# Crowd Machine Examples

This repository contains examples of Crowd Machines applied to numerous supervised classification problems.

# Data set descriptions

We have included four data sets in the `data` directory to demonstrate Crowd Machines. Below are brief descriptions of these data sets.

Every data set is in tab-separated format, with the class label column named `class`. All data sets have been compressed using `gzip` to save disk space.

## GAMETES_Epistasis_2-Way_20atts_0.4H_EDM-1_1

A simulated genetic analysis data set generated using [GAMETES](https://sourceforge.net/projects/gametes/). This data set has 20 columns, but only two of the columns are predictive of the case (1) vs. control (0) outcome when combined.

## Hill_Valley_with_noise

A time series classification data set from the [UCI machine learning repository](https://archive.ics.uci.edu/ml/datasets/Hill-Valley). Each record corresponds to a time series, where all of the features combine to represent the line. The model must be able to classify between a "hill" or "valley" in the time series, with noise added to the time series.

## MNIST

A classic [hand-written digit](http://yann.lecun.com/exdb/mnist/) classification task where the model must classify images as one of nine possible digits (0-9) based on the image input.

## wine-quality-red

A data set from the [UCI machine learning repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality) that challenges the model to classify the quality of various red wines (on a 0-10 scale) based on several measurable features of the wine. This data set can be used as a classification or regression problem.
