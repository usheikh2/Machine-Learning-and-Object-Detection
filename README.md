## Bob's Builders: [Construction Equipment Detection Repository](https://github.com/usheikh2/daen690)

### Table of Contents

 1. [Abstract](#abstract)
 2. [What You Will Learn](#what-you-will-learn)
 3. [Training Infrastructure](#training-infrastructure)
 4. [How to Implement](#implementation)

### Abstract

This project examines heavy equipment safety on construction sites and seeks to automate safety analysis using computer vision and machine learning. Using a Single Shot Detection (SSD) algorithm, this project aims to provide a working model to identify construction equipment using tagged images from construction image data collected by AIRCon-Lab at the University of Alberta along with supplementary images collected by our team from public sources, that were individually tagged by each team member using Microsoft’s Visual object Tagging Tool (VoTT) and RoboFlow. The final TensorFlow records were split into training records, test records, and approximately validation records. _The resulting model produced a total mAP of 0.46, and a large image mAP of 0.48._ Using Google Collab Pro the model was trained in batches of 6 images, over 130,000 training iterations, and with an IOU match threshold of 0.70.

### What You Will Learn
- Employ image processing, manipulation, and feature extraction techniques
- Train distributed models on GPU-based cloud infrastructure, Google Colab Pro
- Tune hyperparameters of object detection model, Single Shot Detection (SSD)
- Build neural network models using TensorFlow, incluinding TensorBoard visuals for mAP, recall, and loss calculation.

### Training Infrastructure

Resources:

- Google Colab (Pro Version)
- Python 3 Google Compute Engine Backend (GPU)
- Available Ram: 25.46 GB 
- Available Disk: 166.83 GB
- About 30 minutes for each 1,000 steps

Pretrained Model: 

·         [SSD ResNet50 V1 FPN 1024x1024 (RetinaNet50)](https://github.com/adityagandhamal/tensorflow-object-detection/blob/master/README.md)
·         TensorFlow 2's Detection Model Zoo
 
 
### Implementation
Here is what you can do to use this project:
  
  - 1] Clone or Download [repository](https://github.com/usheikh2/daen690) from Github to a Google Colab Drive (You must have Google Pro for this).
  
  - 2] Run [Object Dection Model](https://github.com/usheikh2/daen690/blob/main/combine_object_detection.ipynb)

  - 3] Run [Model Evaluation](https://github.com/usheikh2/daen690/blob/main/Model_Evaluations.ipynb) to ouput model calculations and TensorBoard vsiauls.

  
