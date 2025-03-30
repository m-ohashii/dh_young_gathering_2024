# dh_young_gathering_2024
# Clustering Ancient Oriental Literature (Poster Presentation, DH Young Scholars Gathering 2024)

This repository contains the code used in my poster presentation at the **DH Young Scholars Gathering**, held on **July 26–27, 2024**.

## Poster Title
**Analyzing Regional Differences in Ancient Oriental Literature through Text Mining**  
*(Single-authored)*

## Overview
The project aims to identify regional patterns in literary texts from **Ancient Mesopotamia** and **Ancient Egypt** using unsupervised machine learning techniques. The analysis was conducted without disclosing the origin (region) of each text to the model, in order to evaluate whether regional characteristics could emerge naturally from the data.

## Techniques Used
- **TF-IDF vectorization** (`scikit-learn`)
- **Dimensionality reduction** with **PCA**
- **K-means clustering**
- **Data visualization** with `matplotlib`

## File
- `clustering_DH_Young_Scholars_Gathering.ipynb`: The final version of the code used in the poster

## Tools
- Python
- scikit-learn
- pandas
- matplotlib

## Data (Not Included)
The original dataset consists of English-translated texts from the following sources:

- *Sources of Early Akkadian Literature (SEAL)*  
- *Thesaurus Linguae Aegyptiae (TLA)*  

Due to copyright restrictions, the full dataset cannot be shared publicly.  
However, the data was structured as a simple CSV file with two columns:
- English-translated literary texts from:
  - *Sources of Early Akkadian Literature (SEAL)*
  - *Thesaurus Linguae Aegyptiae (TLA)*  

The code provided here can be applied to similar textual datasets.

---
Feel free to explore the notebook and adapt the methods for similar research in digital humanities or computational philology.
