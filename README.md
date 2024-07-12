# Neural Network Vs. Support Vector Machine
The goal for this project is to make a comparison between Neural Networks and Support Vector Machines using a Superbowl Commerical dataset provided from [tidytuesday](https://github.com/rfordatascience/tidytuesday/blob/master/data/2021/2021-03-02/youtube.csv). The comparison is to determine, in this case, which is better to be able to classify and predict an ad as being determined "funny" by a viewer through 6 nominal predictors.

This project uses a SVM optimized by stochastic gradient descent and trained with functions provided by `sklearn` along with fine-tuning parameters through cross-validation, and a Neural Network in which we implemented and trained through our own hyperparameter tuning.

This was done in python, and along in this repo is a report on our findings between the 2 machine learning algorithms.