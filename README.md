# deep-learning-and-neural-networks

Standardization/Normalization: http://yan.lecun.com/exdb/publis/pdf/lecun-98b.pdf

Weights are how neural networks learn.

Weights adjusted as neural networks learn.

Neuron takes a weighted sum of all inputs and runs an activation function.

Activation function decides if the signal is passed or not.

## Types of Activation functions

### Threshold Function

phi(x) => x >= 0 x=1
          x < 0  x = 0

### Sigmoid Function

phi(x) = 1 / (1 + e^-x) (Predicting probability)

### Rectifier Function

phi(x) = max(x,0)

### Hyperbolic Tangent function

phi(x) = 1 - e^-2x / 1 + e^-2x

If Dependant Variable is binary y = 0 or y = 1 -> Threshold or sigmoid.

Big Neural Net: Hidden layer rectifier / Output sigmoid.

Perceptron - Supervised machine learning algo.

Cost Function C = sum( 1/2(^y - y)^2) - updates weights.(how?). Back Propagation

1epoch = 1 dataset processed

http://stats.stackexchange.com/questions/154879/a-list-of-cost-functions-used-in-neural-networks-alongside-applications

## Gradient Descent
Curse of dimensionality - 
