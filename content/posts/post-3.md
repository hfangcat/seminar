---
title: "Hugo Touvron: Training data-efficient image transformers & distillation through attention / Going deeper with Image Transformers"
date: "2021-04-20"
description: "Date and Time: Tuesday, April 20, 1-2 pm"
tags: [Upcoming-seminars]
---

**Title:** Training data-efficient image transformers & distillation through attention / Going deeper with Image Transformers

**Speaker:** Hugo Touvron, Facebook AI Research and Sorbonne University

**Date and Time:** Tuesday, April 20, 1-2 pm

**Place:** [Zoom Meeting](https://kth-se.zoom.us/j/69964216598?pwd=UW5tNHIxZ0wrSER4R3lOVlNaN2U1QT09)

**Meeting ID:** 699 6421 6598       **Pass code:** 600145

**Abstract:** 

**Training data-efficient image transformers & distillation through attention**

Recently, neural networks purely based on attention were shown to address image understanding tasks such as image classification. However, these visual transformers are pre-trained with hundreds of millions of images using an expensive infrastructure, thereby limiting their adoption. 
In this work, we produce a competitive convolution-free transformer by training on Imagenet only. We train them on a single computer in less than 3 days. Our reference vision transformer (86M parameters) achieves top-1 accuracy of 83.1% (single-crop evaluation) on ImageNet with no external data. 
More importantly, we introduce a teacher-student strategy specific to transformers. It relies on a distillation token ensuring that the student learns from the teacher through attention. We show the interest of this token-based distillation, especially when using a convnet as a teacher. This leads us to report results competitive with convnets for both Imagenet (where we obtain up to 85.2% accuracy) and when transferring to other tasks. We share our code and models.
 
**Going deeper with Image Transformers**

Transformers have been recently adapted for large scale image classification, achieving high scores shaking up the long supremacy of convolutional neural networks. However the optimization of image transformers has been little studied so far. In this work, we build and optimize deeper transformer networks for image classification. In particular, we investigate the interplay of architecture and optimization of such dedicated transformers. We make two transformers architecture changes that significantly improve the accuracy of deep transformers. This leads us to produce models whose performance does not saturate early with more depth, for instance we obtain 86.3% top-1 accuracy on Imagenet when training with no external data. Our best model establishes the new state of the art on Imagenet with Reassessed labels and Imagenet-V2 / match frequency, in the setting with no additional training data.

**Bio:** Hugo Touvron is a PhD student at Facebook AI Research and Sorbonne University under the supervision of Hervé Jégou and Matthieu Cord. His research interests are image classification, transfer learning, fine-grained recognition and more generally: the application of transformers in computer vision. Prior to his PhD, Hugo got three MSc from Ecole Polytechnique, ENSTA ParisTech and ENS Cachan.