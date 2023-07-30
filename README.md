# N-GCN-module
This work was done by:
1. Miriam Moscovici
2. Roy Bavly

This repo presents our work of improving the N-GCN network as part of DL course project.
The N-GCN module is presented in the following paper written by Abu-El-Haija et al:
https://paperswithcode.com/paper/n-gcn-multi-scale-graph-convolution-for-semi

The original code of the authors can be seen in the following repository:
https://github.com/samihaija/mixhop

# File Overview
1. mixhop_model.py: Contains the original mixhop layer and model architecture. Our improvement was implemented in this file.
2. mixhop_dataset.py: This reads the [planetoid](https://github.com/kimiyoung/planetoid) datasets (from which we used Cora dataset)
3. ngcn_trainer: same as the original file of the paper's authors.

# How to use
