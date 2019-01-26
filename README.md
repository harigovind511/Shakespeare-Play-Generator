# Shakespeare-Play-Generator

## Overview

A Simple Deep Neural Network trained on Shakespeare Play data corpus, and can be used to generate text in Shakespeare's style.

## Requirements

  * Keras = 2.x (TensorFlow backend)
  * Numpy = 1.x

## Usage

Add text data in Data folder.

Code to create RNN model and to train it is in **Play_Text_Generator.ipynb**.
```
run Play_Text_Generator.ipynb
```

This script will generate model in `./models/` folder.

To generate new text use `generate_text()` which takes in **Seed text, length required, diversity rate**

## Improving Model

1. Training for more epochs.
2. Tweaking Hyper Parameters.
