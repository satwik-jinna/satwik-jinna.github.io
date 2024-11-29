---
layout: page
title: Bias Aware Grid Search, Integrating Fairness into Model Selection
description: Check out this project completed by my 2023-2024 capstone students - Jayson Leach, Anika Garg, Stephanie Chavez, and Ben Chen!
img: bags_project.jpg
importance: 3
category: mentored
---

BiasAwareGridSearchCV is a Python tool created to address a critical need in machine learning: reducing bias. Developed as an extension of scikit-learn, this package helps data professionals build fairer machine learning models by integrating bias into the classical machine learning workflow. It’s designed for situations where decisions could be influenced by factors like gender or race, and where it’s crucial to ensure these decisions are as unbiased as possible.

Our tool stands out by not only measuring model performance in terms of accuracy but also considering how fair a model is. With BiasAwareGridSearchCV, you can evaluate and select models based on both their accuracy and their level of exhibited bias as well as visualize features for a clearer understanding of the trade-offs between bias and accuracy.
The package is user-friendly and fits smoothly into standard machine learning workflows. The figure shows a simplified view of the machine learning process.

Our algorithm is created to be used during the “Hyperparameter Tuning” stage, where the selected model is trained using various parameters and evaluated. Our tool inserts bias consideration into this step by making it a factor in model evaluation alongside traditional performance metrics.

In short, BiasAwareGridSearchCV is our effort to ensure that AI and machine learning contribute positively and fairly to our society, providing tools that help mitigate bias in automated decision-making.

Curious to learn more? Email me and I'll forward you to the team! Or, check out their repo [here](https://github.com/474benchen/bias_aware_gridsearchCV)

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bags_poster.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Student Poster Presented in 2024 Showcase
</div>
