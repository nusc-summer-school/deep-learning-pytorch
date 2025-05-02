Deep Learning with PyTorch NUSC Summer School 2025

Welcome to the Deep Learning with PyTorch workshop for the NUSC Summer School 2025! This repository contains all the materials needed to get started with deep learning using PyTorch.
Workshop Overview
This workshop provides a comprehensive introduction to deep learning concepts and their implementation using PyTorch. Participants will learn how to design, train, and evaluate neural networks for a variety of tasks including computer vision and natural language processing.
Learning Objectives
By the end of this workshop, participants will be able to:

Understand the fundamental concepts of deep learning and neural networks
Implement neural network architectures using PyTorch
Design and train Convolutional Neural Networks (CNNs) for image analysis
Build Recurrent Neural Networks (RNNs) and Transformers for sequence data
Implement transfer learning techniques with pre-trained models
Deploy deep learning models for real-world applications

Prerequisites

Intermediate understanding of Python programming
Basic knowledge of machine learning concepts
Familiarity with linear algebra and calculus fundamentals
A laptop with Python 3.8+ installed (GPU recommended but not required)

Workshop Schedule
Day 1: PyTorch Fundamentals

09:00 - 10:30: Introduction to Deep Learning and PyTorch Basics
10:45 - 12:15: Tensors, Autograd, and Building Your First Neural Network
13:30 - 15:00: Loss Functions, Optimizers, and Training Loops
15:15 - 16:45: Building Multi-Layer Perceptrons for Classification

Day 2: Computer Vision

09:00 - 10:30: Convolutional Neural Networks Architecture
10:45 - 12:15: Training CNNs for Image Classification
13:30 - 15:00: Transfer Learning with Pre-trained Models
15:15 - 16:45: Object Detection and Segmentation

Day 3: Sequence Modeling

09:00 - 10:30: Recurrent Neural Networks and LSTMs
10:45 - 12:15: Transformer Architecture and Attention Mechanisms
13:30 - 15:00: Natural Language Processing with Transformers
15:15 - 16:45: Final Project and Group Presentations

Setup Instructions
Option 1: Using Conda (Recommended)
bash# Clone this repository
git clone https://github.com/nusc-summer-school/deep-learning-pytorch.git
cd deep-learning-pytorch

# Create and activate conda environment
conda create -n pytorch-workshop python=3.10
conda activate pytorch-workshop

# Install PyTorch
conda install pytorch torchvision torchaudio -c pytorch

# Install other required packages
pip install -r requirements.txt
Option 2: Using pip and virtualenv
bash# Clone this repository
git clone https://github.com/nusc-summer-school/deep-learning-pytorch.git
cd deep-learning-pytorch

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install PyTorch
pip install torch torchvision torchaudio

# Install required packages
pip install -r requirements.txt
Repository Structure
deep-learning-pytorch/
├── data/                   # Datasets used in the workshop
├── examples/               # Example code and notebooks
├── exercises/              # Hands-on exercises
│   ├── day1/
│   ├── day2/
│   └── day3/
├── presentations/          # Slide decks in PDF format
├── solutions/              # Exercise solutions
├── models/                 # Pre-trained models and checkpoints
├── project/                # Final project template
├── requirements.txt        # Required Python packages
└── README.md               # Workshop information
Datasets
This workshop uses the following datasets:

CIFAR-10: Image classification dataset with 10 classes
COCO: Object detection and segmentation dataset
IMDb Reviews: Sentiment analysis dataset
WikiText: Language modeling dataset

All datasets will be automatically downloaded through PyTorch's dataset utilities.
Resources
Recommended Reading

Stevens, E., Antiga, L., & Viehmann, T. (2020). Deep Learning with PyTorch. Manning Publications.
Géron, A. (2022). Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow. O'Reilly Media.

Online Resources

PyTorch Documentation
PyTorch Tutorials
Dive into Deep Learning with PyTorch

Instructors

Prof. Michael Chen - Deep Learning Researcher, Stanford University

GitHub | LinkedIn


License
This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments
We would like to thank all contributors and the NUSC Summer School organizing committee for making this workshop possible.

For questions or additional information, please contact us at info@nuscsummerschool.edu
