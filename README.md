# Machine Learning & Python Projects

A collection of Python and machine learning projects completed during my Bachelor of Science (Statistics) studies.

This repository documents my practical experience in data preprocessing, statistical modelling, neural networks, and model evaluation.

## Featured Project: Abalone Age Classification

**Tools:** Python, Pandas, NumPy, Scikit-learn, Jupyter Notebook

### Project Overview

Developed and evaluated machine learning models to classify abalone into age groups using physical measurements from 4,177 observations.

### Methodology

- Conducted exploratory data analysis and applied categorical encoding, outlier handling, feature scaling, and feature engineering.
- Trained fully connected neural networks with varying hidden-layer depths, widths, and SGD/Adam optimisers.
- Evaluated model performance across 10 random seeds.
- Compared neural network performance against a logistic regression baseline.

### Results

| Model | Mean Test Accuracy |
|---|---:|
| Best Neural Network | 79.44% |
| Logistic Regression Baseline | 78.08% |

The best neural network achieved a modest improvement over logistic regression, suggesting that additional model complexity provided limited accuracy gains for this classification task.

### Key Learning Outcomes

- Building end-to-end machine learning workflows
- Comparing neural network architectures and optimisation algorithms
- Conducting repeated experiments for model evaluation
- Interpreting predictive performance and model complexity

**Notebook:** [Abalone Neural Network Analysis](abalone-neural-network-analysis.ipynb)

---

## Other Projects

### Linear Regression on the Diabetes Dataset

Explored linear regression and statistical modelling using the Diabetes dataset, with a focus on implementing and understanding regression techniques in Python.

**Notebook:** [Linear Regression on the Diabetes Dataset](Linear%20Regression%20on%20the%20Diabetes%20Dataset.ipynb)

### Python Programming Fundamentals

A collection of introductory Python exercises and learning notes covering essential programming concepts.

**Notebook:** [Basics of Python Programming](Basics%20of%20Python%20Programming.ipynb)

---

## Technical Skills

- **Programming:** Python
- **Libraries:** NumPy, Pandas, Scikit-learn
- **Machine Learning:** Linear Regression, Logistic Regression, Neural Networks
- **Data Analysis:** EDA, Feature Engineering, Data Preprocessing
- **Tools:** Jupyter Notebook, GitHub
