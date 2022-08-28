# California-Housing
A self-learning exercise in training a MLP Regression Model to predict California housing price with TensorFlow 2.

Model: MLP Regression Model\
Layers:
1. Dense(30,relu)
2. Dense(1)

## Conclusion
The model does not perform as well as expected, there is rooms for improvement in prediction accuracy.\
Mean MedHouseVal: 2.0686\
RMSE: 0.6111

This means that the predicted housing price is averagely about 30% off from the actual housing value.\
As we can notice that the train and validation loss are close together, it is likely that the model is somewhat underfitting the data.\
We can increase the complexity of the model (increasing layers, increasing neurons per layer, change activation functon, change loss function etc).
