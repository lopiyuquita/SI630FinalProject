# SI630FinalProject

---

Yuko López, School of Information, the University of Michigan (04-30-2019)

---

## Overview

This repository contains Python scripts for building binary classifiers using logistic regression (LR) 
and latent Dirichlet allocation (LDA).  This is a part of SI630 (Natural Language Processing) at School of Information, 
the University of Michigan in Winter 2019.

---  

## Dataset

An unlabeled job description dataset was uploaded
from Kaggle, which is publicly available in a csv file from monster.com job postings
in 2017.  I labeled the 215 job descriptions out of 22000.  The labels consist of five classes, 
each of which are treated as binary classifier.  Some job descriptions have one class, 
while others have multiple classes.  

---  

## Algorithm

1. LR (Base Model)

2. LR and LDA (Better Model)
    * LDA: Topic results to feed back into the Logistic Regression to benefit from hidden topics
and to improve the quality of the classifier, also to potentially mitigate
the heuristics I unintentionally might have applied during the partial labeling process.

---  

## Packages
1. Scikit-learn
2. Numpy
3. Pandas
4. NLTK
5. Seaborn




