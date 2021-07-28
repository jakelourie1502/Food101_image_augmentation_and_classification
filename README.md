##### OVERVIEW: This repo estimates the increase in classification performance that can be achieved through augmentation of images to increase the size of the dataset.

I run a resnet classifier on 3 different categories of food, downloaded from the Food101 dataset available via tensorflow to establish a baseline classification performance. I then perform various image augmentations (crop, mirror and rotation) and use the same ResNet model to classify the image set.

RESULT: The image augmentations lead to an increase in classification performance from 57% to 71%
