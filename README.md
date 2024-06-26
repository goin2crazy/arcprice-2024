# ARCPrice-base

This repository contains the baseline code for training a convolutional neural network (CNN) model to predict the next values in a matrix. The baseline includes resizing matrices at the beginning (to `tf.data.Dataset`) and building a TensorFlow model. The training process utilizes a learning rate scheduler and early stopping as callbacks.

## Baseline

- Matrix resizing to `tf.data.Dataset` format
- TensorFlow model construction
- Learning rate scheduler and early stopping callbacks for training

## Requirements

- Python 3.x
- TensorFlow
- NumPy
- Pandas
- Matplotlib

## Installation

Clone the repository and install the required packages:

```bash
git clone https://github.com/yourusername/ARCPrice-base.git
cd ARCPrice-base
pip install -r requirements.txt
