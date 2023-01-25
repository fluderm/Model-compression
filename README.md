# Model compression

Here we play around with various approaches to model compression using the example of the CIFAR10 dataset and using a straightforward convolutional network in Jax. We focus on the linear layers and employ SVD and related compression techniques to investigate the inference time speedups vs accuracy vs model memory.
