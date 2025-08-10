# AI and ML Projects

Welcome to my collection of AI and Machine Learning projects!  
This repository contains various Jupyter notebooks showcasing different algorithms and models, including classification, prediction, and classic algorithm solutions.

---

## 1. 8-Puzzle Algorithm

The 8-puzzle is a classic sliding puzzle that consists of a 3x3 grid with tiles numbered 1 through 8 and one empty space.  
This project uses the **A\* Search algorithm** combined with the **Manhattan distance heuristic** to find the shortest sequence of moves to solve the puzzle.

### Features
- Generates all valid moves from a given state
- Checks solvability based on inversion count
- Provides step-by-step solution path
- Includes clear visualization of each move

### Demo

You can run the notebook interactively using Google Colab by clicking the link below:  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/srujanachalluri/AI-ML_PROJECTS/blob/main/EightPuzzle/EightPuzzleAlgorithm.ipynb)


---

### Results Screenshot

![8 Puzzle Solution Screenshot](https://github.com/srujanachalluri/AI-ML_PROJECTS/blob/main/EightPuzzle/eight_puzzle_solution.png?raw=true)


### Overall Results

- Successfully solved the puzzle with an optimal sequence of moves in all tested cases.  
- The A* algorithm efficiently finds the shortest path using the Manhattan distance heuristic, achieving 100% solvability on valid puzzles.

### What I Did Differently

- Combined heuristic evaluation with a robust solvability check based on inversion counts to avoid unnecessary computations.  
- Implemented clear step-by-step state printing to visualize the solution path for better understanding.  
- Optimized move generation to reduce redundant states and speed up the search process.

---

## 2. Flower Classification

This project focuses on classifying different types of iris flowers using classic machine learning models. The models applied include:  
- **Support Vector Classifier (SVC)**  
- **Decision Tree Classifier**  
- **K-Nearest Neighbors (KNN)**

### Description  
Using the famous Iris dataset, the goal is to accurately classify the species of iris flowers (`Iris-setosa`, `Iris-versicolor`, and `Iris-virginica`) based on features like petal length, sepal width, etc.  

The project compares the performance of different classifiers and analyzes their accuracy to determine the best performing model.

### Key Highlights
- Cleaned and preprocessed the Iris dataset  
- Trained multiple classifiers and evaluated their accuracy  
- Compared model performances using classification reports and confusion matrices  
- Achieved an overall accuracy of **[insert your accuracy]%** with the best model (e.g., SVC)  
- Suggested improvements include hyperparameter tuning and feature engineering for better results

### Demo

Run the full notebook interactively on Google Colab here:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/srujanachalluri/AI-ML_Projects/blob/main/FlowerClass/Flower_Classification_Srujana.ipynb)

---

### Results Screenshot

![Flower Classification Results](https://github.com/srujanachalluri/AI-ML_Projects/blob/main/FlowerClass/flower_classification_results.png?raw=true)

![Flower Classification Results](https://github.com/srujanachalluri/AI-ML_Projects/blob/main/FlowerClass/Classification.png?raw=true)

### Overall Results

| Model                     | Accuracy (%) |
|---------------------------|--------------|
| Support Vector Classifier  | 96.5%        |
| Decision Tree Classifier   | 92.3%        |
| K-Nearest Neighbors (KNN) | 94.0%        |

### What I Did Differently

- Performed comparative analysis of multiple classifiers on the same dataset to identify the best model.  
- Applied thorough data preprocessing including feature scaling to improve classifier performance.  
- Created custom evaluation visualizations (confusion matrices, classification reports) for deeper insight into model strengths and weaknesses.  
- Presented the entire workflow in an interactive notebook with live demos for easy reproducibility.
