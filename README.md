Automated Waste Classification Using Deep Learning

This repository contains a Jupyter notebook developed for the course
Project: Computer Science (DLMCSPCSP01).

The project explores the use of computer vision and deep learning to classify waste materials from images. The goal is to investigate whether image-based classification can support more accurate and efficient waste sorting in recycling systems.

Dataset
The project uses the TrashNet dataset, a publicly available dataset for waste classification.

Total number of images: 2527
Number of classes: 6
Classes: cardboard, glass, metal, paper, plastic, trash

The dataset shows class imbalance, especially in the trash category. Dataset exploration and preprocessing are performed inside the notebook.

Notebook Content
The notebook includes the following steps:

Loading and exploring the dataset

Image preprocessing (resizing)

Splitting data into training and testing sets

Model development using transfer learning

Model training

Model evaluation using standard classification metrics

Tools and Environment
Programming language: Python
Deep learning framework: PyTorch
Execution environment: Google Colab
Additional libraries: NumPy, Matplotlib

All experiments were executed in Google Colab. No local installation is required.

Repository Structure
AI_Powered_Waste_Sorting_System_Using_Deep_Learning.ipynb
README.txt

How to Run
Open the notebook in Google Colab, upload or mount the TrashNet dataset, and run the cells in order.

Project Status
This repository represents the Phase 2 (Development and Reflection Phase) of the project. Further improvements and extended evaluation are planned for Phase 3.

License
This repository is intended for academic and educational purposes only.
