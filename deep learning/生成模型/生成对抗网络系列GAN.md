参考：

1. [论文：Generative Adversarial Networks](https://arxiv.org/abs/1406.2661)

2. https://kikaben.com/understanding-generative-adversarial-networks/

3. [GAN (Generative Adversarial Network): Simple Implementation with PyTorch](https://kikaben.com/gangenerative-adversarial-network-simple-implementation-with-pytorch/)

4. [[How to Train a GAN? Tips and tricks to make GANs work](https://github.com/soumith/ganhacks#how-to-train-a-gan-tips-and-tricks-to-make-gans-work)]

5. [Generative Models](https://github.com/wiseodd/generative-models)

6. https://github.com/naokishibuya/deep-learning/blob/master/python/gan_mnist.ipynb

7. [很棒的仓库Collection of generative models, e.g. GAN, VAE in Pytorch and Tensorflow](https://github.com/wiseodd/generative-models)

   ![thumbnail](./../../示例图片/thumbnail.png)

要点：

1. 很难训练，训练技巧：[[How to Train a GAN? Tips and tricks to make GANs work](https://github.com/soumith/ganhacks#how-to-train-a-gan-tips-and-tricks-to-make-gans-work)]
2. 训练过程，一个批量数据，三次更新梯度：
   - real_image—**discriminator**
   - fake_image—**discriminator**
   - latent_sample—**generator**—fake_image—**discriminator**(not trainable)