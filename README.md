# GENERATIVE ADVERSARIAL NETWORK (GAN)

### 1. GAN on MNIST Handwritten Data

Generative Adversarial Network are generative models. There are two networks, Generator Network and Discriminator Network. Both Network competes with each other. Generator Network generates Fake images which are criticised by Discriminator whether the image is fake or real. Generator aim is to produce fake images and to fool Discriminator in such a way that Discriminator classify it as real.

GANs were [first reported on](https://arxiv.org/abs/1406.2661) in 2014 from Ian Goodfellow and others in Yoshua Bengio's lab.

![](https://github.com/parth1620/Generative-Adversarial-Net-MNIST/blob/master/images/GAN%20MNIST.png)

### Results

![](https://github.com/parth1620/Generative-Adversarial-Net-MNIST/blob/master/images/GAN.jpg)

![](https://github.com/parth1620/Generative-Adversarial-Net-MNIST/blob/master/images/overall%20result%20gan.png)



### 2. DCGAN on MNIST Handwritten Data



GAN using convolutional layers in the generator and discriminator. This is called a Deep Convolutional GAN, or DCGAN for short.The DCGAN architecture was first explored in 2016 and has seen impressive results in generating new images; you can read the [original paper, here](https://arxiv.org/pdf/1511.06434.pdf).

Here I have used DCGAN architecture on MNIST Handwritten dataset.

![](https://github.com/parth1620/Generative-Adversarial-Net-MNIST/blob/master/images/DCGAN%20MNIST.png)

### Results

![](https://github.com/parth1620/Generative-Adversarial-Net-MNIST/blob/master/images/DCGAN.jpg)

![](https://github.com/parth1620/Generative-Adversarial-Net-MNIST/blob/master/images/overall%20result%20dcgan.png)
