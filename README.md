# Multi-label-Classification-with-Exploratory-Data-Analysis

Introduction

This repository contains the code for a multi-label classification project based on the Multi-label Classification of enzyme substrates dataset. The dataset consists of various molecular features, and the goal is to predict two binary targets, denoted as EC1 and EC2. 

Dataset Description

train.csv: The training dataset contains six binary targets, [EC1 - EC6], but the objective is to predict EC1 and EC2. This dataset was generated from a deep learning model trained on a subset of features from the original dataset, which had the most signal.

test.csv: The test dataset contains the same features as the training data. The objective is to predict the probability of the two targets, EC1 and EC2, for the instances in the test dataset.

Features

The dataset includes various molecular features that are potentially relevant for predicting enzyme substrate labels. Here is a brief description of the features:

BertzCT: Bertz counter value associated with the structural complexity of the molecule.

Chi1, Chi1n, Chi1v: Kier's First-order Molecular Connectivity Index, representing the molecular surface area.

Chi2n, Chi2v, Chi3v: Kier's Second-order and Third-order Connectivity Index, representing the 2nd and 3rd degree connectivity of the molecule.

Chi4n: Kier's Fourth-order Connectivity Index, representing the 4th degree connectivity of the molecule.

EState_VSA1, EState_VSA2: EState-VSA (E-State Value Sum) 1 and 2, representing the electrotopological state contributions of the molecule.

ExactMolWt: Exact molecular weight of the molecule.

FpDensityMorgan1, FpDensityMorgan2, FpDensityMorgan3: Density values of the Morgan fingerprint.

HallKierAlpha: Hall-Kier Alpha value of the molecule, describing its core structure.

HeavyAtomMolWt: Molecular weight of atoms in the molecule, excluding hydrogen atoms.

Kappa3: Kappa-3 shape index of the molecule, describing its topology.

MaxAbsEStateIndex: Maximum absolute E-State index of the molecule, representing its maximum charge state.

MinEStateIndex: Minimum E-State index of the molecule, representing its minimum charge state.

NumHeteroatoms: Number of heteroatoms (non-carbon atoms) in the molecule.

PEOE_VSA10, PEOE_VSA14, PEOE_VSA6, PEOE_VSA7, PEOE_VSA8: PEOE (Partial Equalization of Orbital Electronegativity) VSA (Value Sum) 10, 14, 6, 7, 8, representing the partial charge surface area contributions of the molecule.

SMR_VSA10, SMR_VSA5: SMR (Simple Molecular Representation) VSA 10, 5, representing the similarity model radius surface area contributions of the molecule.

SlogP_VSA3: SlogP (Substructure-logP) VSA 3, representing the logarithm of the partition coefficient of the molecule.

VSA_EState9: E-State-VSA (E-State Value Sum) 9, representing the electrotopological state contributions of the molecule related to its surface area.

fr_COO, fr_COO2: The number of carboxyl groups in the molecule.

Exploratory Data Analysis (EDA)

To better understand the dataset and prepare for modeling, an Exploratory Data Analysis (EDA) was conducted. The EDA included the following:

Data Summary: An overview of the dataset's basic statistics, such as mean, standard deviation, and quartiles.

Data Visualization: Visualization of feature distributions, correlations, and any patterns that emerged.

Feature Engineering: Creating new features or preprocessing existing ones based on insights from the EDA.

Target Analysis: Understanding the distribution of the target variables (EC1 and EC2) and their relationships with features.

Missing Data Handling: Dealing with missing values, if any.

Outlier Detection: Identifying and addressing outliers in the data.

Model Selection: Choosing appropriate machine learning algorithms for multi-label classification based on EDA findings.

Conclusion

This repository provides the code and documentation for a multi-label classification project on enzyme substrate prediction. The EDA performed on the dataset is crucial for understanding the data's characteristics and for building effective predictive models. The information in this README serves as a starting point for anyone interested in working with this dataset and problem.
