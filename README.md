# Gan Network Experiments

Generative Adversary Networks (GANs) are architectures of deep neural networks composed of two networks pitted against each other. This is one of the newest and most fascinating architectures in Deep Learning. 

This project aims to show the application of the network in some conventional datasets.

#### Basic architecture of the GAN network:

<img align="center" alt="serie" src="https://raw.githubusercontent.com/macio-matheus/gan-network-experiment/master/docs/network-gan.png" data-canonical-src="https://raw.githubusercontent.com/macio-matheus/gan-network-experiment/master/docs/network-gan.png" height="300" />

#### Result of 1000 epochs

<img align="center" alt="serie" src="https://raw.githubusercontent.com/macio-matheus/gan-network-experiment/master/docs/800.png" data-canonical-src="https://raw.githubusercontent.com/macio-matheus/gan-network-experiment/master/docs/800.png"  height="300" />

#### Usage

##### Run with docker compose

```sh
 cd gan-network-experiment
 docker-compose up -d --build
```

Go to #local-ip#:8111/lab and run the "gan-network-experiments.ipynb" notebook to observe the exploration process

##### TODO: 
    - Do more experiments
