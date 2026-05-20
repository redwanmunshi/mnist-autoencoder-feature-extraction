# MNIST Autoencoder Feature Extraction

This project builds and trains a fully connected autoencoder on the MNIST handwritten digit dataset using PyTorch.

The model compresses each 28x28 image into a 16-dimensional bottleneck representation and reconstructs the original image from this latent vector.

## Methods
- Fully connected encoder-decoder architecture
- Mean squared error reconstruction loss
- Adam optimiser
- PCA analysis of latent features
- Reconstruction error comparison by digit class
- Latent space interpolation

## Results
- Final training MSE: 0.017365
- Test MSE: 0.017603
- PCA explained variance: 28.64% and 23.82% for the first two principal components

## Tools
Python, PyTorch, NumPy, scikit-learn, Matplotlib
