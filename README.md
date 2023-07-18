# Remove_Sky

# Computer Vision Assignment - Sky Removal

This assignment focuses on manipulating a dataset by removing the sky from the images using a deep learning model. The goal is to create a new dataset that contains the same information and images as the original dataset but without the sky.

## Problem

When creating a dataset for training, sometimes we want to manipulate the dataset without the need to re-annotate the images. In this assignment, we aim to remove the sky from the images while preserving the annotations.

## Solution

To solve the problem, we will use a random dataset since we couldn't find a specific dataset with images containing the sky. We will run a program to detect the sky using a deep learning model and create COCO annotations for the dataset. Finally, we will create a script to manipulate the dataset and remove the sky.

## Tasks

1. Download a random dataset that contains images.
2. Run the program to detect the sky in the images.
3. Create COCO annotations for the dataset.
4. Implement a script to manipulate the dataset and remove the sky.
5. Validate the modified dataset by displaying the images and annotations on the screen.

## Environment

- Framework: Detectron2 (Facebook framework)
- Base: Python + OpenCV library
- Notebook: Google Colaboratory or Jupyter on a local GPU machine

## Getting Started

1. Clone the repository:

   ```shell
   git clone https://github.com/your_username/computer-vision-assignment.git
