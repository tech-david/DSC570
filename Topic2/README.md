# Topic 2
Contains Decision Tree and Naive Bayes method classification for PerformanceDecision dataset.  Salary and age have been binned in intervals of 5, where 1-5=1, 6-10=2, 11-15=3, etc.  Full dictionary for values has been amended at the end of the readme file.

## Requirements
The code was written in Jupyter Notebook using Python 3.  Any imports used were initially brought pip install.  Please refer to documentation for each individual library for instructions, if needed. 

## Decision Tree
Decision Tree has modeled us scikit-learn's library.  The program will save a png image to working directory, but an output is also displayed if using Jupyter Notebook or Google Colab.

## Naive Bayes
Two versions of Naive Bayes was implemented, Categorical and Gaussian.  Both had similar results.  Data was preprocessed by making 'salary' and 'status' as ordinal values. Labels were created for 'department' to turn them into numerical values.  Training and testing data was created using train_test_split.

## Data Discovery
Raw data visualizations including relational bar plots, and a pairplot.

## Dictionary
- [26...30] = 5
- [31...35] = 6
- [36...40] = 7
- [41...45] = 8
- [46...50] = 9
- [55...60] = 10
- [66...70] = 14