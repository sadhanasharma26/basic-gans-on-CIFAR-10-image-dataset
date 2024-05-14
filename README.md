# Basic GANS on CIFAR-10 Image Dataset
 
## Introduction
The provided code implements a Generative Adversarial Network (GAN) using PyTorch to generate images. The GAN consists of a Generator and a Discriminator trained adversarially to generate realistic images. The dataset used for training is CIFAR-10, a popular dataset containing 60,000 32x32 color images in 10 classes.

The Generator learns to create images that are indistinguishable from real images, while the Discriminator learns to differentiate between real and generated images. The training process involves optimizing the Generator and Discriminator iteratively to improve the quality of generated images.

The Generator takes random noise as input and generates images, while the Discriminator classifies images as real or fake. The GAN framework aims to find a Nash equilibrium where the Generator produces realistic images and the Discriminator cannot differentiate between real and generated images.

By training on the CIFAR-10 dataset, the GAN learns to generate images resembling the objects in the dataset, showcasing the power of GANs in creating synthetic data.
This code demonstrates the training process of a GAN on the CIFAR-10 dataset, showcasing the interplay between the Generator and Discriminator in generating realistic images.

## About the Dataset
The CIFAR-10 Image Dataset is a widely used benchmark dataset in the field of computer vision. It consists of 60,000 32x32 color images across 10 classes, with each class containing 6,000 images. The dataset is split into 50,000 training images and 10,000 test images, making it suitable for training and evaluating image classification models.

### Key details about the CIFAR-10 dataset include:
* Dataset Size: The CIFAR-10 dataset has a download size of 162.17 MiB and a dataset size of 132.40 MiB.
* Features: Each image in the dataset is structured as a FeaturesDict containing an ID, the image itself (32x32x3), and a label indicating the class (int64).
* Supervised Keys: The dataset is supervised, with keys 'image' and 'label' used for supervised learning tasks.
* Classes: The dataset includes 10 classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

## Reference for code & tutorial: 

```diff
https://www.geeksforgeeks.org/generative-adversarial-network-gan/?ref=lbp
```
## To clone this repository, use:

```diff
https://github.com/sadhanasharma26/basic-gans-on-CIFAR-10-image-dataset.git
```
