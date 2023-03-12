### Jake Ryan

## Background


An explanation of DL for medical imaging (linked with resources), and the state of training data.

## Introduction

### An Brief Explanation of the Paper "Deep Learning Radiographic Assessment of Pulmonary Edema: Optimizing Clinical Performance, Training With Serum Biomarkers"

Explaining the basis of this paper (quiet briefly), giving audience an understanding into the biological science behing the ML.

### The Idea Behind The Work

Explain the basis of how past paper leads to hypotheses of new work.

#### The Hypotheses

List the two hypotheses being put to the test

## The Data 

### UCSD Data

### MIMIC Data
Breakdown of Hsiao Data and MIMIC data

## The Models

There are four models: a model trained with full images and biomarker-based labels (UCSD Full), a model trained with full images and radiologist confirmed labels (MIMIC Full), a model trained with anatomically segmented images and biomarker-based labels (UCSD Segmented), and a model trained with anatomically segmented images and radiologist confirmed labels (MIMIC Segmented).

Each model is based on a ResNet 152v2 with pretrained weights from the ImageNet dataset. 
<details>
<summary>What is ResNet 152v2 and what is ImageNet?</summary>
<br>

The ResNet 152v2 is an image classification model built by Microsoft that is renowned for its use of [residual connections](https://towardsdatascience.com/what-is-residual-connection-efb07cab0d55), a technique that allows networks to have a large amount of layers without losing its ability to predict.

ImageNet is an industry standard dataset often used to benchmark classification model performance. Models trained to perform on ImageNet have developed a feature space that is adept at predicting many different classes of things that may be in the image. It is a great 'starting place' for models trained on niche tasks, like this one.
</details> 



## Biomarkers Work (or Biomarkers Do Not Work (Yet))

Mix of word explanation of results with tables, graphs, images, code, and saliency
