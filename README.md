# Fact Checker for Climate

This repository aims to create a machine fact checker for climate claims, utilizing BERT for embedding creation and fine-tuning. Given a set of ground truths stored in (`evidence.json`, which was not uploaded due to its large size), the fact checker classifies climate-related claims into four categories: `REFUTES`, `SUPPORTS`, `DISPUTED`, and `NOT_ENOUGH_INFO`.

## Data

The data used in this project are sourced from COMP90042, University of Melbourne.

## Requirements

- [Colab](https://colab.research.google.com/)

## Result

- validation accuracy: 0.49
- validation F1 score: 0.46

<img src="img/label-distribution.png" alt="label-distribution" width="400"/>

This project did not use a traditional training-validation/test split because the original task's test set lacks labels. Training was performed on the training set, while evaluation was conducted on the development set.

## Project Background

This project is a modification of Project 3 from Natural Language Processing (COMP90042) at the University of Melbourne, Semester 1, 2024.
