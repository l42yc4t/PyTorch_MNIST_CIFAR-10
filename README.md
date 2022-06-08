# PyTorch_MNIST_CIFAR-10
Training MNIST with CNN and CIFAR-10 with ResNet-18 both in PyTorch.

Note: 
1. I train CIFAR-10 with setting device("mps") with my M1 Macbook, cause I failed with using device with("cpu") to load my model in. With this setting 
outputs = net(inputs) should get a better performance.

2. If you are using Models.resnet on MNIST dataset, you should modify the input channels to 1 (original setting for CIFAR-10 RGB channels is 3).

3. I used https://github.com/kuangliu/pytorch-cifar code in this repo. If you wanna know more details, go ahead and check this up.
