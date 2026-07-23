# Week 2 – Machine Learning Foundations

## AI vs ML vs Analytics vs Rules

### What is AI?
Artificial Intelligence (AI) is the broad field of creating systems that can perform tasks that normally require human intelligence, such as reasoning, learning, or understanding language. An example is a virtual assistant like ChatGPT.

### What is Machine Learning?
Machine Learning is a branch of AI that enables computers to learn patterns from data and make predictions without being explicitly programmed. For example, predicting hospital bed demand from historical hospital data.

### What is Analytics?
Analytics focuses on examining historical data to understand what happened and support decision-making. For example, analyzing last month's hospital admissions and occupancy rates

### What are Rule-Based Systems?
Rule-based systems follow predefined "if-then" instructions created by humans. For example, if hospital occupancy exceeds 90%, send an alert to hospital management.

### When is ML better than Rules?
Machine learning is better when patterns are complex and change over time. Rules are better when the decision is simple, predictable, and clearly defined.

## Machine Learning Loop

1. Define the problem
2. Collect or generate data
3. Prepare the data
4. Train the model
5. Evaluate the model
6. Improve the model
7. Deploy and monitor


## Supervised vs Unsupervised Learning

### Supervised Learning
Supervised learning uses labelled data where the correct answer is known. The model learns to predict the target variable.
### Unsupervised Learning
Unsupervised learning works with unlabeled data and discovers hidden patterns or groups without a target variable.

## Generalization vs Overfitting

### Generalization
Generalization is when a machine learning model performs well on new, unseen data instead of only the data it was trained on.

### Overfitting
Overfitting happens when a model memorizes the training data instead of learning useful patterns, causing poor performance on new data.


# Applying ML to My Capstone

## Search Question

Can historical hospital activity predict tomorrow's hospital bed demand?

## ML Task Type

Regression (Scoring)

## Target Variable

Daily hospital bed demand

## Features

- Emergency admissions
- Scheduled admissions
- Discharges
- Flu cases
- Occupancy rate
- Available staff

## Decision

Help hospital administrators plan beds and staffing.

## Success Metric

Mean Absolute Error (MAE)
