# MNIST
MNISTで試したモデル

(環境)
Python 3.7 
PyTorch 1.3.1
CUDA 10.2


DCGANのlossと生成結果(epoch = 100)

<img src=https://github.com/kyamada101/MNIST/blob/master/images/MNIST_DCGAN.png width=350pix> | <img src=https://github.com/kyamada101/MNIST/blob/master/images/DCGAN.gif>


conditional GANのlossと生成結果(epoch = 100)

<img src=https://github.com/kyamada101/MNIST/blob/master/images/MNIST_cGAN.png width=350pix> | <img src=https://github.com/kyamada101/MNIST/blob/master/images/cGAN.gif>

WGANのlossと生成結果(epoch = 500, Generatorは5エポック毎に更新)

<img src=https://github.com/kyamada101/MNIST/blob/master/images/MNIST_WGAN.png width=350pix> | <img src=https://github.com/kyamada101/MNIST/blob/master/images/WGAN.gif>
