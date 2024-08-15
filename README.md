# deep-neural-network-step-by-step
 
This project provides a comprehensive step-by-step guide to building a deep neural network from scratch. It covers all the necessary concepts and implementations, from initializing parameters to forward and backward propagation, and finally updating the parameters. The goal of this project is to help you understand the underlying mechanics of a deep neural network.

## Table of Contents
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Features](#features)

## Installation Instructions

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your local machine.
- Jupyter Notebook installed for running `.ipynb` files.
- Install the required libraries using pip:

```bash
pip install numpy h5py matplotlib
```

### Installation Guide

To clone this repository, run

    ```bash
    git clone https://github.com/justinliu23/deep-neural-network-step-by-step.git
    ```

## Usage

To use this project, follow these steps:

1. After installation, launch Jupyter Notebook as described above.
2. Open the `Deep_Neural_Network_Step_by_Step.ipynb` file.
3. Run each cell sequentially to build each component of the deep neural network.

The notebook is organized to guide you through the entire process, starting from parameter initialization to the final model training.

## Features

- **Layer-wise Implementation**: The project includes detailed implementations for each layer of the neural network, including initialization, forward propagation, backward propagation, and parameter updates.
- **Custom Activation Functions**: Implementation of ReLU and Sigmoid functions and their derivatives for use in the network.
- **Cost Function**: Calculation of the cross-entropy cost to evaluate the performance of the network.
- **Backpropagation**: Comprehensive backpropagation implementation that supports multi-layer neural networks.
