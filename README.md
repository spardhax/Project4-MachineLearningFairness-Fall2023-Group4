# Project 4: Machine Learning Fairness

### [Project Description](doc/project4_desc.md)

Term: Fall 2023

+ Team 4
+ Projec title: Comparing Machine Learning Fairness Algorithms
+ Team members
	+ Ritika Nandi
	+ Spardha Sharma
	+ Wenhe Chen
	+ Zan Li
    + Yichuan Lin
	+ Yuchen Wu

+ Project summary: In this project, we have explored 2 methods for *Machine Learning Fairness* i.e. to correcting the unfairness for certain groups or individuals in machine learning algorithms' predictions on the [COMPAS](https://www.propublica.org/datastore/dataset/compas-recidivism-risk-score-data-and-analysis) dataset. The aim of the project is to predict the two-year-recidivism of black and white defendants while holding racial status as a sensitive attribute to prevent machine bias against black defendants.

Algorithms used - 
1. [Maximizing accuracy under fairness constraints (C-SVM and C-LR)] (https://arxiv.org/pdf/1507.05259.pdf) - This algorithms focuses on maximizing accuracy under fairness constraints by minimizing the loss function subject to a covariance threshold between race (sensitive attribute) and the decision boundary.

2. [Information Theoretic Measures for Fairness-aware Feature selection (FFS)] (https://arxiv.org/pdf/2106.00772) - This algorithms algorithm uses the joint statistics of the data to derive two information theoretic measures that can be used to quantify the accuracy and discrimination aspect for each subset of the feature space. We then evaluated each model's performance using accuracy and calibration.

	
**Contribution statement**: RN and SS worked on A2, Maximizing accuracy under fairness constraints (C-SVM and C-LR). RN worked on C-SVM and SS worked on C-LR. WC, ZL, YL, and YW worked on A7, Information Theoretic Measures for Fairness-aware Feature selection (FFS)
.

 This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
