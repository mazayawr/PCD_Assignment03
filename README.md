# PCD Assignment 03
### Image Segmentation and Morphological Processing

**Name:** Mazaya Nurina  
**NIM:** 25/554758/PA/23236

## Overview

This assignment focuses on image segmentation and morphological processing using a rice grain image. Otsu's thresholding was implemented manually to separate the rice grains from the background, followed by four morphological operations: erosion, dilation, opening, and closing. All methods were implemented without using built-in image processing functions.

## Results

The segmentation produced a binary image that separates the rice grains from the background using an Otsu threshold value of 101. After applying morphological processing, some small gaps were filled and the foreground regions became more continuous. However, some neighboring rice grains also became connected.

Overall, the experiment shows how morphological operations can modify and refine segmentation results, while also affecting the shapes and boundaries of objects.
