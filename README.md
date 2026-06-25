# data-lab

A hands-on journey through NumPy, Pandas, and Matplotlib — from math simulations to image processing.

I'm working through these projects to build the practical foundation I'll need as an AI Engineer. Before touching any ML framework, I want to actually understand what's happening under the hood.

---

## Level 1 — Syntax & Vectorized Thinking

### 1. Time-Series Data Analysis
Using a public CSV dataset (Ho Chi Minh City weather data or Vietnam COVID data) to get comfortable with real, messy data.

- Loading and cleaning CSV files, handling missing values
- Grouping by month/quarter, computing mean and standard deviation
- Drawing line charts over time and bar charts comparing regions

### 2. Math Simulation & Visualization
Simulating things from scratch to build intuition for how NumPy actually works under the hood.

- Plotting mathematical functions
- Simulating random walks
- Estimating Pi with Monte Carlo

The real goal here is to stop reaching for Python loops and start thinking in vectors.

---

## Level 2 — Real-World Data Analysis

### 3. Exploratory Data Analysis (EDA)
Picking a Kaggle dataset — likely Titanic, House Prices, or a Vietnamese dataset like national exam scores — and running a full EDA pipeline.

- Load → clean → describe → visualize → write up insights
- Histograms, boxplots, correlation heatmaps

EDA is something every AI Engineer does constantly. Getting fluent at it early matters.

### 4. ML Algorithms from Scratch
Implementing Linear Regression, Logistic Regression, and K-Means using raw NumPy — no sklearn.

- Plotting decision boundaries and loss curves over epochs
- Understanding the math before reaching for a library

This is probably the most important project in the whole repo. If I can build these from scratch, I'll understand what PyTorch and scikit-learn are actually doing for me later.

---

## Level 3 — Tying It Together

### 5. Image Processing (No OpenCV)
Reading images as NumPy arrays and building the operations myself.

- Grayscale conversion, convolution (blur, sharpen, edge detection), histogram equalization
- Plotting pixel value distributions

Convolution here is the same operation inside every CNN. Doing it manually once makes the concept stick permanently.

### 6. Mini Analytics Dashboard
Pulling everything together into one cohesive project. Probably an analysis of film/anime ratings data.

- Multi-panel report using Matplotlib subplots
- Optionally exported as PDF

---

## Why this order

Project 4 is the one I care most about. Understanding how gradient descent and loss functions work at the NumPy level is the clearest path toward writing and debugging real ML models later — which is exactly where I want to end up.

Everything else builds toward that.