# PetEarNet – Detecting Cat Ears with AI

Final project for the Building AI course

## Summary

PetEarNet is an AI-based computer vision project that explores how cat ears can be detected in images using simple image processing and artificial intelligence techniques. The project demonstrates how basic AI concepts such as convolution and pattern recognition can be applied to real-world problems.

## Background

Monitoring pets and understanding their behavior can be challenging, especially when owners or caregivers are not physically present. Visual cues such as ear position often indicate whether an animal is alert, relaxed, or stressed, but constant manual observation is not practical.

This project aims to address:
* The difficulty of continuously monitoring pets remotely
* Limited awareness of how simple AI techniques can detect visual features
* The need for beginner-friendly AI projects with real-world relevance

My personal motivation is to better understand how AI interprets images and how simple filters and models can detect meaningful shapes. This topic is interesting because it shows that even basic AI methods can already provide useful insights.

## How is it used?

The solution would be used in environments where pets are monitored using cameras, such as homes, animal shelters, or veterinary clinics. A user provides an image (or video frame), and the system highlights areas where cat ears are likely to be detected.

Potential users include:
* Pet owners
* Animal caregivers
* Students learning AI and computer vision

The solution should take into account different lighting conditions, camera angles, and ethical considerations such as privacy when using cameras.

## Data sources and AI methods

The project can use publicly available images of cats from open datasets or Creative Commons sources. Images may also be collected personally with proper permission.

Possible data sources include:
* Open image datasets
* Kaggle pet image datasets
* Creative Commons images

AI methods used:
* Image preprocessing (grayscale conversion, normalization)
* Convolution filters for edge and shape detection
* Optional extension: Convolutional Neural Networks (CNNs) for automatic feature learning

## Challenges

This project does not:
* Fully interpret animal emotions or intentions
* Work reliably in very poor lighting or low-quality images
* Automatically generalize to all animal breeds and poses without sufficient data

Limitations include sensitivity to lighting, background noise, and limited training data. Ethical considerations include responsible use of cameras and respect for privacy.

## What next?

Possible future improvements include:
* Training a neural network to automatically learn ear features
* Extending detection to other animals such as dogs
* Using video streams instead of single images
* Developing a simple web or mobile application

Further development would require more data, stronger machine learning skills, and collaboration with animal behavior experts.

## Acknowledgments

* Inspired by the Building AI / Elements of AI course by the University of Helsinki
* Open-source learning materials on computer vision and neural networks
* Publicly available datasets and Creative Commons images used for educational purposes
