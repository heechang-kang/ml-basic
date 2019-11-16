# Deep Learning

- Geoffrey Hinton : wrote paper about DL

## comments

- categorical data -> LabelEncoding(turns string to num), OneHotEncoder(num to not in order) 
- batch learning : num of samples to work through before updating model

## ANN : Artificial Neural Network

### Steps

- Neuron
- Activation Function
- How it works
- How it learns
- Gradient Descent
- Stochastic Gradient Descent
- Backpropagation

### Neuron

dendrites, neuron, axon

input_value(standardized) -> Neuron -> output_value

### Activation Function

### ANN with Stochastic GradientDescent

1. randomly initialize weights
2. input data
3. forward propagation
4. compute the error
5. back-propagation
6. repeat 1-5 and update(RL) or update only after a batch of observation(Batch learning)
7. redo more epochs
