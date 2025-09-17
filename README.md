# data-augmentation-gans
Exploring how to augment datasets with Generative Adversarial Networks (GANs) in PyTorch.

## Overview

This project implements a Generative Adversarial Network (GAN) from scratch using PyTorch to augment existing datasets. GANs consist of two neural networks that work against each other:

- A Generator that creates synthetic data samples
- A Discriminator that tries to distinguish real from generated samples

Through adversarial training, the Generator learns to produce increasingly realistic data that matches the distribution of the original dataset.

## Key Components

- PyTorch for implementing and training the neural networks
- Automatic differentiation for computing gradients during training
- Matplotlib for visualizing the training process and generated samples
- Custom architectures for both Generator and Discriminator networks

## Goals

1. Build a robust GAN implementation from scratch
2. Train the model to generate high-quality synthetic data
3. Use the trained Generator to augment existing datasets
4. Analyze and visualize the quality of generated samples
5. Compare performance of models trained with and without augmented data

## Requirements

- PyTorch
- Matplotlib
- NumPy
- Python 3.11+

# Tasks
- Tasks 0: