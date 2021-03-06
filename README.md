# Impact of Fully Connected Layers on Performance of Convolutional Neural Networks for Image Classification
This research is carried out to find the necessity of fully connected (FC) layers in CNN for image classification.

## Abstract
The Convolutional Neural Networks (CNNs), in domains like computer vision, mostly reduced the need for handcrafted features due to its ability to learn the problem-specific features from the raw input data. However,  the selection of dataset-specific CNN architecture, which mostly performed by either experience or expertise is a error-prone process. To automate the process of learning a CNN architecture, this letter attempts at finding the relationship between Fully Connected (FC) layers with some of the characteristics of the datasets. The CNN architectures, and recently data sets also, are categorized as deep, shallow, wide, etc. This letter tries to formalize these terms along with answering the following questions. (i) How the deeper/wider datasets influence the necessity of FC layers in CNN?, (ii) What is the impact of deeper/shallow architectures on the number of required FC layers?, and (iii) Which kind of architecture (deeper/ shallower) is better suitable for which kind of (deeper/ wider) datasets. To address these, we have performed experiments with three CNN architectures having different depths. The experiments are conducted by varying the number of FC layers. We used four widely used datasets including CIFAR-10, CIFAR-100, Tiny ImageNet, and CRCHistoPhenotypes to justify our findings with respect to the impact of fully-connected layers in image classification.


The objective of the paper is represented using the below figure.

![alt text](https://github.com/shabbeersh/Impact-of-FC-layers/blob/master/Impact_FC_layers_CNN.png)


For more details, please read our [paper](https://arxiv.org/abs/1902.02771).

## Requirements
Keras >= 2.1.2 <br/>
Tensorflow-gpu >= 1.2

## Acknowledgements
The few blocks of code are taken from [here](https://github.com/geifmany/cifar-vgg).

## Citations
@article{basha2019impact,
  title={Impact of Fully Connected Layers on Performance of Convolutional Neural Networks for Image Classification},
  author={Basha, SH and Dubey, Shiv Ram and Pulabaigari, Viswanath and Mukherjee, Snehasis},
  journal={arXiv preprint arXiv:1902.02771},
  year={2019}
}
