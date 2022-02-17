# Weibull Modelling Case-Study for Ground Engaging Tools

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description
In this sample project the aim is to demonstrate how reliability analyses can be conducted in Python with real-world data.
The intended outcome of the modelling is to allow us to estimate some properties of the reliability of a system, or of a component of a system, including predicting the mean time-to-failure (MTTF).

This Python project was heavily inspired by the original analysis of this data in R: [Reliability Analysis in R](https://systemhealthlab.com/research-tools/example-of-a-reliability-analysis-in-r/).

## Usage/Installation
1. Download the project: https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository
2. Download & Install Jupyter: https://jupyter.org/install
3. Run the Jupyter Notebook titled `weibull-python.ipynb`

## Sections
There are 4 distinguished sections of the analysis:
1. **Preamble**
  - Outlines the objectives of the analysis and provides important context for the problem.
2. **Load required packages, functions and dataset**
  - Prepares the development environment
  - Loads the dataset using the package `Pandas`
3. **Graphical Analysis**
  - First viewing of the data which allows for sanity checking
4. **Fit models and estimate parameters**
  - Fits the parameters of a Weibull distribution to the dataset using numerical methods.
5. **Inference**
  - Use our model to make predictions about the reliability of the system

## Authors and acknowledgment
Sophie Giraudo

## License
This project is licensed under the permissive MIT license.
