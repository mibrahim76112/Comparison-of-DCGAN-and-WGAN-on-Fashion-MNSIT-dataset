# Comparison of DCGAN and WGAN on Fashion MNIST Dataset

A deep learning project that compares **DCGAN** and **WGAN-GP** on the **Fashion MNIST** dataset.
This repository studies how two popular generative adversarial network architectures perform when trained to generate fashion item images from noise.

The project is useful for understanding the differences between standard GAN training and Wasserstein based training, especially in terms of training stability and image generation quality.

---

## Project Overview

This repository contains two separate Jupyter Notebooks for comparing GAN models on the Fashion MNIST dataset.

The first notebook implements a **DCGAN** model, while the second notebook implements a **WGAN-GP** model. Both are trained on the same dataset so their behavior and generated image quality can be compared in a consistent setting.

The goal of the project is to explore how architectural and loss function differences affect generative performance on grayscale fashion images.

---

## Features

- Comparison of DCGAN and WGAN-GP
- Training on the Fashion MNIST dataset
- Notebook based implementation
- Image generation from random noise
- Study of GAN training behavior
- Practical comparison of model stability and output quality
- Useful for academic learning in deep learning and generative AI

---

## Repository Structure

```text
Comparison-of-DCGAN-and-WGAN-on-Fashion-MNSIT-dataset/
│
├── Program_8_DCGAN_1.ipynb      # DCGAN implementation on Fashion MNIST
├── Program_9_WGAN_GP_Q1.ipynb   # WGAN-GP implementation on Fashion MNIST
└── README.md                    # Project documentation
```

---

## Models Included

### DCGAN

Deep Convolutional GAN uses convolutional layers in both the generator and discriminator.
It is a popular GAN architecture for image generation and is often used as a baseline model in generative learning tasks.

### WGAN-GP

Wasserstein GAN with Gradient Penalty is an improved GAN variant designed to provide more stable training.
Instead of using the standard GAN loss, it uses the Wasserstein distance along with gradient penalty to reduce training problems such as mode collapse and unstable convergence.

---

## Dataset

The project uses the **Fashion MNIST** dataset.

Fashion MNIST is a grayscale image dataset containing clothing-related categories such as shirts, trousers, dresses, shoes, and bags.
It is commonly used as a benchmark dataset for machine learning and computer vision experiments.

---

## Comparison Goal

The purpose of this project is to compare the two GAN approaches on the same dataset and study differences such as:

- training stability
- image quality
- convergence behavior
- ease of implementation
- overall generative performance

This comparison helps in understanding why Wasserstein based GANs are often preferred for more stable training.

---

## Workflow

1. Load the Fashion MNIST dataset.
2. Preprocess the images for GAN training.
3. Train the DCGAN model using one notebook.
4. Train the WGAN-GP model using the second notebook.
5. Generate synthetic fashion images from random noise.
6. Compare the visual quality and training behavior of both models.

---

## Notebook Details

### `Program_8_DCGAN_1.ipynb`

This notebook contains the implementation of the DCGAN model.
It focuses on standard GAN based training using convolutional generator and discriminator networks.

### `Program_9_WGAN_GP_Q1.ipynb`

This notebook contains the implementation of WGAN-GP.
It is used to compare a more stable Wasserstein based training setup against DCGAN.

---

## Tools and Technologies

- Python
- Jupyter Notebook
- Deep Learning framework
- Fashion MNIST dataset
- Generative Adversarial Networks
- DCGAN
- WGAN-GP

---



