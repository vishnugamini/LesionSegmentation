# Skin Cancer Cells Segmentation using UNet with Squeeze and Excitation Block

## Introduction

This repository contains the implementation of a deep learning model for segmenting skin cancer cells using the UNet architecture with a Squeeze and Excitation (SE) block. The model achieved an impressive accuracy of 93% on the validation set. The dataset used for training and evaluation consists of 20,000 images, including both images and corresponding masks.

Skin cancer is a significant health concern worldwide, and accurate segmentation of cancerous cells is crucial for early detection and effective treatment. The UNet architecture, coupled with the SE block, has proven to be highly effective in various medical image segmentation tasks due to its ability to capture detailed spatial information.

## Dataset

The dataset used for this project comprises 20,000 images of skin tissue samples, along with their corresponding masks that indicate the regions of cancerous cells. The dataset is diverse and representative of various skin cancer types, which helps ensure the model's generalization.

Please note that the original dataset may be subject to specific usage licenses, and it is essential to provide appropriate attribution and comply with any terms and conditions set forth by the dataset's creators.

## Model Architecture

The model architecture used in this project is based on the UNet, a popular deep learning architecture for image segmentation tasks. Additionally, we integrated the Squeeze and Excitation (SE) block into the UNet to enhance feature recalibration and improve the model's performance.

The UNet architecture is known for its contracting and expansive paths, which enables it to capture context information and retain spatial details efficiently. The Squeeze and Excitation block further refines the feature maps by recalibrating channel-wise feature responses, which helps in focusing on informative regions while suppressing irrelevant ones.

## Model Performance

After extensive training and hyperparameter tuning, the model achieved an impressive accuracy of 93% on the validation set. The segmentation outputs demonstrate high precision in identifying cancerous cells and effectively segmenting them from the surrounding healthy tissue.

## Usage

To use the code provided in this repository, follow these steps:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/skin-cancer-cells-segmentation.git
