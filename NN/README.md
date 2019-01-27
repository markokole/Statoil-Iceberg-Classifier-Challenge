## About

The playbook `Neural Network from Scratch` has 2 classes:
- `prepare_data` - reads the data from JSON into Pandas, does some transformation and converts the columns to Numpy arrays for further transformation
- `mlp` - short for multilayer perceptron - takes in training, validation and test Numpy arrays. The model is trained, validated and a small part of the dataset is used for testing.

MLP is written for scratch - only Numpy library is used. As per now, only one hidden layer is available, with `number of neurons` being one of the input parameters. The idea is to make the mlp class take in a new argument - `number of hidden layers` - and have a neural network with multiple hidden layers.

## Run
From the Kaggle's Statoil Iceberg Classifier Challenge, download the data and save them under root directory in the repository.
The notebook can be run when data is available. The parameters can be adjusted to do some further testing.
