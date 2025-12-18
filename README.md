# final-assignment

# Mechanisms of Visual Distractor Interference: A DDM Analysis

**Student:** Sarah Lobis  
**Course:** Cognitive Modelling  
**Date:** December 2025  

## Project Overview
This repository contains the Python code and analysis for the final assignment on Drift Diffusion Modeling (DDM). 

Data Pipeline: Preprocessing of reaction time data (Dataset 6), outlier removal, and trial stratification.

The project investigates the effect of visual distractors on lexical decision making (Dataset 6) by fitting and comparing three competing DDM variants:
1.  **Drift Model:** Distractors affect sensory evidence accumulation ($v$).
2.  **Boundary Model:** Distractors affect response caution ($a$).
3.  **Bias Model:** Distractors affect starting point bias ($z$).

Analysis: Individual subject fitting using Robust Likelihood, BIC-based model selection, and Goodness-of-fit visualization via Defective CDFs.

## Requirements
The analysis is written in Python 3 and requires the following libraries:

* `numpy`
* `pandas`
* `matplotlib`
* `seaborn`
* `pyddm` (Paranoid Scientist)

## Installation
You can install the required packages using pip:

`pip install numpy pandas matplotlib seaborn pyddm`

## How to Run
To execute the analysis, launch the notebook and run all cells sequentially:

```bash
jupyter notebook final_assignment.ipynb