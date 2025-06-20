# Inference-and-Evaluation-of-MedSAM-2-on-Brain-Tumor-Segmentation-BRATS-2019-

-------------------------------------------------------------------------------------------------

## 📌 Overview

This project focuses on evaluating the inference performance of **MedSAM-2**, a medical imaging version of the Segment Anything Model (SAM), on the **BRATS 2019** dataset for brain tumor segmentation. MedSAM-2 is designed to perform zero-shot segmentation on medical scans by using prompt-based inputs like bounding boxes or points.

The goal of this project is to assess how well MedSAM-2 can generalize to brain MRI images without additional training. Using the T1ce modality from BRATS 2019, we analyze MedSAM-2's ability to segment whole tumor regions by comparing its predictions against the ground truth annotations. The evaluation includes visual segmentation overlays and quantitative metrics such as Dice score and IoU.

This work provides insights into the model’s potential and limitations in medical applications, particularly in scenarios where annotated data or fine-tuning resources are limited.

-------------------------------------------------------------------------------------------------

## ✨ Features

- 🔍 **Zero-shot inference** on BRATS 2019 using MedSAM-2
- 📊 **Qualitative and quantitative** comparison of predictions with ground truth
- 🖼️ **Visualization** of segmentation masks overlaid on MRI scans
- ⚙️ Easy-to-run code with minimal configuration
- 📁 Organized structure for reproducible results

-------------------------------------------------------------------------------------------------

## 🧠 MedSAM-2 Architecture

MedSAM-2 is a domain-adapted version of Meta AI’s **Segment Anything Model (SAM)**, tailored for medical imaging tasks. It leverages:

- **ViT-based encoder** to capture contextual and spatial features from grayscale medical images
- **Prompt-based segmentation**, enabling region-specific inference (e.g., bounding boxes or points)
- **Multi-modal fusion** of image and prompt embeddings for robust segmentation
- **Fine-tuned on multi-organ medical segmentation datasets**, including CT and MRI images

MedSAM-2 supports both **bounding-box prompts** and **point prompts** for guidance.

-----------------------------------------------------------------------------------------------------

## 🧬 Dataset: BRATS 2019

The **Brain Tumor Segmentation Challenge (BRATS)** dataset provides multi-modal MRI scans of glioma patients, along with manual annotations for:

- **Enhancing tumor (ET)**
- **Tumor core (TC)**
- **Whole tumor (WT)**

Dataset Link: https://www.kaggle.com/datasets/aryashah2k/brain-tumor-segmentation-brats-2019/data


-----------------------------------------------------------------------------------------------------

🚀 Results:

![image](https://github.com/user-attachments/assets/f5a6f81c-67b5-448a-bd5e-9b1c8461968c)

![image](https://github.com/user-attachments/assets/918aa5ed-e8e0-49c9-93a6-6a4edc03a081)

![image](https://github.com/user-attachments/assets/d9a3ddb2-4544-4bf9-a90c-baae3b9b4789)

-----------------------------------------------------------------------------------------------------

📚 References:

https://www.kaggle.com/datasets/aryashah2k/brain-tumor-segmentation-brats-2019/data
https://www.kaggle.com/datasets/awsaf49/brats2020-training-data
https://github.com/bowang-lab/MedSAM2



