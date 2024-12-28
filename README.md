## Abstract
This paper is a partial implementation of a 2006 paper by Caruana and Niculescu-Mizil (Caruana & Niculescu-Mizil, 2006). It is implemented as a part of the final project for the course COGS 118: Supervised Machine Learning Algorithms, taughtby Professor Tu Zhuowen. The paper will look at three different classification algorithms, performed using three different splits, and on three
different datasets taken from the UC Irvine Machine Learning Repository.

## Introduction
Classification algorithms are extremely crucial in machine
learning, where the intent is to classify and find patterns
in places where we might not be able to discern using the
human eye. Classification has historically been a crucial
pillar of machine learning, since it is simply human nature
to find patterns in everything.

This paper aims to implement three classification algorithms
to evaluate their performance on binary classification tasks:
Random Forest, Decision Tree, and Support Vector Machine
(SVM). A full breakdown of each classification will be
provided in Section 2: Methodology.

This was conducted as part of a final assignment to gain experience with implementing classification
algorithms on real-world datasets, taken from the UC Irvine
Machine Learning Repository, which is widely used in machine learning research. The datasets were ensured to have
no missing values, and they are adjusted for binary classification. In order to show representative performance,
cross-validation was performed accross three different partitions.

To comply with course requirements, these implementations were taken by Caruana et.al’s 2006 paper (Caruana &
Niculescu-Mizil, 2006) on evaluating performances of different algorithms. Each algorithm was trained under three
test partitions: 80/20, 20/80, and 50/50, using a averaged
accuracy amongst the three splits to determine performance
evaluation.

The primary objectives of this paper are:

• To implement and evaluate the performance of Random
Forest Classification, Support Vector Machine Classification, and Decision Tree Classification Algorithms.

• To analyze the impact that a dataset has (Data size,
instances, features, etc.) on model performance

• To compare said results from the other two objectives
with the results found in the original paper (Caruana &
Niculescu-Mizil, 2006)
