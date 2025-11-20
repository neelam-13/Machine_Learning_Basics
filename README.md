# Machine Learning Basics – Core Methods & Implementations

This repository contains a collection of machine learning notebooks that I completed during my Master’s program as part of the course exercises.  
Although I did not design the assignments themselves, I worked through all implementations, visualizations, and analyses to deepen my understanding of core machine learning concepts.

The notebooks span a wide range of foundational ML techniques, from unsupervised learning to ensemble methods.

---

## About

This repository highlights my practical understanding of fundamental machine learning techniques through clean, structured implementations and visual explanations.

If you're reviewing this as part of an application, I'm happy to walk through any notebook in more detail!

---

## Highlights
- Hands-on practice with PCA, ICA, MDS, Isomap, k-NN, AdaBoost, Random Forests, and more  
- Strong focus on understanding *how and why* algorithms behave the way they do  
- Extensive visualizations and comparisons between methods  
- Practical experience with NumPy, SciPy, scikit-learn, matplotlib, and Jupyter  

---

# Notebooks Overview

## 1. Unsupervised Learning: PCA, ICA, and Sparse Coding
Worked with MNIST and Olivetti datasets to explore multiple feature extraction techniques.  
Includes visualization of learned components and reconstruction of image patches.

---

## 2. Manifold Learning: MDS and Isomap
Implemented:
- Multidimensional Scaling (MDS)  
- Isomap (using nearest-neighbor graphs + geodesic distances + MDS)  

These notebooks helped illustrate how nonlinear datasets (e.g., Swiss roll) can be represented more meaningfully in lower dimensions.

---

## 3. Classification: k-Nearest Neighbors
Applied the k-NN algorithm to a 2D dataset.  
Compared models for different values of *k* and visualized decision boundaries to understand their behavior.

---

## 4. Boosting: AdaBoost
Followed the step-by-step construction of AdaBoost using threshold-based weak learners.  
Analyzed how each boosting round improves performance and alters the decision boundary.

---

## 5. Ensemble Methods: Random Forests
Built a simplified Random Forest using:
- Random feature selection  
- Bootstrapped (bagged) datasets  
- Out-of-bag (OOB) error estimation  

Visualized how combining many simple trees leads to better stability and overall performance.

---

# Skills Demonstrated
- Applying and understanding core ML algorithms  
- Visualizing and interpreting model behavior  
- Working with synthetic and image-based datasets  
- Ensemble methods (boosting, bagging, random forests)  
- Dimensionality reduction and manifold learning  
- Strong use of Python scientific libraries (NumPy, SciPy, scikit-learn, matplotlib, Jupyter)  

---

# Running the Project


To run the notebooks locally:

```bash
# Clone the repository
git clone https://github.com/neelam-13/Machine_Learning_Basics.git

# Move into the project folder
cd your-repo

# Launch Jupyter Notebook
jupyter notebook

---

# License
This project uses the MIT License.

The MIT License allows others to use, modify, and share the code (including commercially) as long as the license file is included.  
The code is provided without warranty.

These notebooks were part of my Master’s coursework.  
Please use them responsibly and do not submit them as academic work.