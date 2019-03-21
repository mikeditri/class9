# cebd1160_project_template
Instructions and template for final projects.

| Name | Date |
|:-------|:---------------|
|Michael D'Itri | 2019-03-21|

-----

### Resources
Your repository should include the following:

- Python script for your analysis
- Results figure/saved file
- Dockerfile for your experiment
- runtime-instructions in a file named RUNME.md

-----

## Research Question

Based on 13 different chemical compenents of wine, can we predict from which of the 3 different cultivators the wine originates? 

### Abstract

4 sentence longer explanation about your research question. Include:

- opportunity (what data do we have):

The data is comprised of thirteen different measurements taken for different constituents found in the three types of wine (3 different origins). 

- action (how will we try to solve this problem/answer this question)

Leveraging this data, we may be able to determine the relationship between the chemical composition of wine, which could then be used to classify wine that has lost its label.

- resolution (what did we end up producing)

Based on the performance of the "Insert Clustering model name", we found that the model was fairly consistent and could be used as a relatively good for determining the origin of the wine.

### Introduction

Brief (no more than 1-2 paragraph) description about the dataset. Can copy from elsewhere, but cite the source (i.e. at least link, and explicitly say if it's copied from elsewhere).

The data is the results of a chemical analysis of wines grown in the same region in Italy by three different cultivators
. There are thirteen different measurements taken for different constituents found in the three types of wine.
 (https://scikit-learn.org/stable/datasets/index.html#wine-dataset)


### Methods

Brief (no more than 1-2 paragraph) description about how you decided to approach solving it. Include:

- pseudocode for this method (either created by you or cited from somewhere else)
- why you chose this method
The method used for modelling this data was Naive Bayes Classifier built into scikit-learn. 

Pseudocode: https://scikit-learn.org/stable/modules/naive_bayes.html

The reason why we chose Naive Bayes is because it works well with a small training set, is extremely fast.
Also, The decoupling of the class conditional feature distributions means that each distribution can be independently estimated as a one dimensional distribution. This in turn helps to alleviate problems stemming from the curse of dimensionality. (https://scikit-learn.org/stable/modules/naive_bayes.html)

Secondly, we found another group who ran the same data set through multiple classifiers and showed that Naive Bayes had one of the best performances (>95%). (https://jonathonbechtel.com/blog/2018/02/06/wines/)


### Results

Brief (2 paragraph) description about your results. Include:

- At least 1 figure
- At least 1 "value" that summarizes either your data or the "performance" of your method
- A short explanation of both of the above
![alt text](https://github.com/mikeditri/class9/blob/master/Gaussian_NB_with_Accuracy.png)


### Discussion
Brief (no more than 1-2 paragraph) description about what you did. Include:

- interpretation of whether your method "solved" the problem
- suggested next step that could make it better.

### References
All of the links

-------
