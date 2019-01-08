###### Goal:

To perform validations on model.

###### Implementation:

Implemented the following validation techniques,

1. Hold out validation
2. Leave one out validation
3. K-fold cross validation

###### Observation:

It is always necessary to carry out validation on your model to see how the model perform outside the sample to a new data set.

The motivation to use cross validation techniques is that when we fit a model, we are fitting it to a training dataset. Without cross validation we only have information on how does our model perform to our in-sample data. Ideally we would like to see how does the model perform when we have a new data in terms of accuracy of its predictions.
