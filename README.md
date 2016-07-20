# Residual Networks Test

Original Paper: Deep Residual Learning for Image Recognition
By [Kaiming He](http://research.microsoft.com/en-us/um/people/kahe/), [Xiangyu Zhang](https://scholar.google.com/citations?user=yuB-cfoAAAAJ&hl=en), [Shaoqing Ren](http://home.ustc.edu.cn/~sqren/), [Jian Sun](http://research.microsoft.com/en-us/people/jiansun/).

Microsoft Research Asia (MSRA).

### Introduction

This repository contains the models for testing resnet networks on cifar-10

Data augmentation applied: max_color_shift = 5, contrast_variation = 0.8 ~ 1.2, max_brightness_shift = 5, zero-padding with 2 pixels for each side and crop with 32x32

50000 samples for training, batch size 250, 200 iterations for 1 epoch, 64000 iterations in total
10000 samples for testing, test batch size 100 and 100 test iterations
reduce learning rate after 32000 iters by factor of 10
then another factor of 10 after anohter 16000 iters

Resnet-20: best model achieved 0.9268 accuracy on test datasets
Resnet-32:
Resnet-56:

