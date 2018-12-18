## humpback-whale-identification

### Install

This project requires **Python 3.7.0** and the following Python libraries installed:

* fastai
* pytorch

Getting started with humpback-whale-identification challenge. 
* The data for this competition can be found [here](https://www.kaggle.com/c/humpback-whale-identification)



**Steps followed while training my model**
* Remove smaples with *new whale* label.
* do, not split training data into training and validation (we do not want to miss the rare cases)
* train our model with the best hyperparamters.
* include samples with *new whale* lables
* retrain our model with very littel learning rate
* predict the test labels
* see the the validation score on the public leaderboard.
