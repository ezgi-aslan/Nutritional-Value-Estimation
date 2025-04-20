# Nutritional Value Estimation

## Overview

The **Nutritional Value Estimation** project aims to develop a computer vision-based system that predicts the nutritional values of food items on a plate by recognizing their constituent ingredients. Using state-of-the-art deep learning techniques, the system estimates the quantity of food and calculates its nutritional content, empowering users to make informed dietary choices.


## Motivation

With the rise of health-conscious lifestyles, accurate dietary assessment tools are more critical than ever. Traditional methods of tracking nutritional intake are often time-consuming and prone to errors. This project leverages advancements in computer vision and machine learning to provide an efficient, accurate, and accessible solution for dietary assessment. By automating the process, we aim to revolutionize how individuals monitor their nutrition and promote healthier living.


## Dataset

We utilize [**Nutrition5k** dataset](https://github.com/google-research-datasets/Nutrition5k), a comprehensive resource for visual nutrition understanding. The dataset includes:

- **5,006 realistic plates of food** with detailed ingredient metadata.
- **Overhead RGB-D images** and rotating side-angle videos for enhanced visual analysis.
- Ground truth nutritional values for algorithm training and evaluation.

This dataset enables the development and benchmarking of robust food recognition and nutritional estimation algorithms.


## Methodology

Our approach involves the following key steps:

1. **Data Preprocessing**: Cleaning and organizing the dataset, handling missing values, and standardizing data formats.
2. **Deep Learning Models**: Developing multi-label learning models for food recognition and nutritional estimation.
3. **Training and Fine-Tuning**: Training the models on the Nutrition5k dataset and optimizing hyperparameters for improved performance.
4. **Evaluation**: Assessing the models using metrics such as Mean Absolute Error (MAE), Root Mean Square Error (RMSE), and correlation coefficients.
5. **Refinement**: Analyzing results to identify areas for improvement and iteratively refining the models.


## Quantitative Experiments

To validate our approach, we conduct rigorous experiments on the Nutrition5k dataset. Key performance metrics include:

- **Mean Absolute Error (MAE)**: Measures the average magnitude of errors in predictions.
- **Root Mean Square Error (RMSE)**: Evaluates the standard deviation of prediction errors.
- **Correlation Coefficients**: Assesses the strength of the relationship between predicted and actual values.

These metrics ensure the reliability and precision of our system.


## Progress Plan

To ensure timely progress and successful completion, we follow this structured plan:

1. **Data Preprocessing**: Clean and organize the dataset, handle missing values, and standardize formats.
2. **Model Development**: Build deep learning models for food recognition and nutritional estimation.
3. **Training**: Train models on the dataset and fine-tune hyperparameters.
4. **Evaluation**: Test models on training and testing splits using appropriate metrics.
5. **Analysis and Refinement**: Analyze results, identify areas for improvement, and refine models.
6. **Reporting**: Prepare a comprehensive progress report summarizing methodology, results, and future directions.


## Poster

Below is a visual summary of our project. For a detailed view, refer to `poster.png`:

![Project Poster](poster.png)



## Contributors

- Ezgi Aslan - [https://github.com/ezgi-aslan](https://github.com/ezgi-aslan)
- Beyza Nur Bozkurt - [https://github.com/beyzanurbozkurt](https://github.com/beyzanurbozkurt)
- Zeynep Begüm Baş - [https://github.com/begumaktann](https://github.com/begumaktann)

