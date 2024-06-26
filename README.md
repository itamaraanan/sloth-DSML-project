# Sloth Species Classification Project

## Project Overview
This project is part of the Data Science and Machine Learning final assessment, developed by me, Itamar Raanan. It focuses on the classification of different sloth species using a dataset from Kaggle. The dataset includes various features such as claw length, size, tail length, weight, and the endangered status of six distinct sloth species.

## Features
The dataset includes the following attributes for each sloth:
- **Specie**: Type of sloth (two-toed, three-toed)
- **Sub Specie**: Specific species names
- **Weight (kg)**: Weight of the sloth
- **Size (cm)**: Height of the sloth
- **Claw Length (cm)**: Length of the sloth’s claw
- **Tail Length (cm)**: Length of the sloth’s tail
- **Endangered Status**: Conservation status (least concern, vulnerable, critically endangered)

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/itamaraanan/sloth-DSML-project.git]
   ```
2. Install required libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```

## Usage
1. Load the Jupyter Notebook provided in the repository.
2. Run the cells to observe the data preprocessing, feature engineering, and the machine learning models in action.## Models Used
- **K-Nearest Neighbors (KNN)**: For predicting the sloth species based on the nearest data points.
- **Support Vector Machine (SVM)**: Used for classification between the species with different kernels tested for optimization.
- **Perceptron**: A simple linear classifier used as another method to validate the performance across different models.

## Results
The project achieved high accuracy in classifying the sloth species, with detailed confusion matrices and classification reports provided to assess model performance.

## Conclusion
This project effectively used machine learning to classify sloth species. With models like K-Nearest Neighbors, Support Vector Machine, and Perceptron, it achieved high accuracy. It provided me valuable experience in working with biological data for wildlife conservation.
