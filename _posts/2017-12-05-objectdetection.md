---
layout:     post
title:      'Object Detection with R-CNN Family'
date:       2017-12-05 09:00:00
summary:    R-CNN, Fast R-CNN, Faster R-CNN
categories: blog rcnn
---

Convolution Neural Networks (CNNs) are widely used, majorly for the purpose of image classification (classifying an object in an image into one of the given categories) and have shown to perform very well on huge datasets (for example, the ImageNet challenge [link]). Even with the huge success <replace this> of CNNs in classification, the task of actually understanding an image still remains a challenge. One such task that corresponds to image understanding is object detection, wherein the task is to detect objects in an image and specify where these objects appear in the image (using a bounding box or masking etc.).

Several algorithms have been proposed to solve the task of object detection, and one such class of methods to be discussed in this post is the R-CNN family of algorithms (R-CNN [], fast R-CNN [], faster R-CNN [], Mask R-CNN []).

## R-CNN

R-CNN, or __Regions with CNN features__, is a method for object detection proposed in 2014

--
 