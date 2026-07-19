# M26
Official implementation for the paper "Entropy-Based Active Learning for Earth Observation and Astrophysics Data Classification". This repository contains the complete code to reproduce all experiments from the paper, including cross-domain evaluation on Fermi-GBM GRB classification and Air Quality UCI dataset.

Key Features:
- Pool-based active learning with three query strategies: Max Entropy, Min Entropy, and Random sampling
- Logistic regression classifier with uncertainty-based sample selection
- Reproducible experiments across 5 random seeds
- Comprehensive evaluation metrics (accuracy, ROC-AUC, confusion matrices)
- Support for two scientific domains: astrophysics and Earth Observation

Repository Structure:
- Data preprocessing pipeline with stratified sampling
- Active learning loop (4 rounds, 50 samples per round)
- Passive learning and full-data training baselines
