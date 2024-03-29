# CNN-PCAM-Tumour-Classification

As part of my Foundations of Deep Learning course at CentraleSupélec, I trained a CNN using PyTorch on 10% of the PatchCamelyon ([PCAM](https://github.com/basveeling/pcam?tab=readme-ov-file)) dataset which consists of 32768 96x96px images from histopathology patches of lymph nodes. These images are labelled with a 0 (not containing any tumour tissue) and 1 (containing tumour tissue). 

The goal of the project was to classify unseen histopathology patches distinguishing those containing tumour tissue from those devoid of it.

It is recommended to run the code in Google Colab using the GPU for faster training.
