# Resnet
 
## 1. Trainning
 - Initalizing Conv layer using He initialization
 - Cifar 10 dataset, RandomCrop, RandomHorizontalFlip, RandomRotation
 - Increase dimension using 1x1 conv layer
 - 300 epochs
 - Lr 0.01 until error rate belows 80%, then change to 0.1 (ResNet56, ResNet110)

## 2. Result
Model | Error Rate(in paper) | Error Rate(implement)
---|:---:|:---:
**ResNet18** | x | 7.49 
**ResNet34** | x | 6.94 
**ResNet56** | 6.97 | 6.77
**ResNet110** | 6.43 | 6.10


## 3. Other ResNet
 - ResNet110 6.25 (https://github.com/kuangliu/pytorch-cifar)
 - ResNet110 6.32 (https://github.com/akamaster/pytorch_resnet_cifar10)
