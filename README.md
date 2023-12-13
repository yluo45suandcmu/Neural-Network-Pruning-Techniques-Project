# Neural-Network-Pruning-Techniques-Project

## Overview
This repository contains the implementation and analysis of various neural network pruning techniques. The project's primary goal was to explore methods to reduce model complexity while preserving performance. It includes implementations of magnitude-based pruning, L1-norm based filter pruning, and channel pruning applied to a pre-trained neural network model.

## Techniques Implemented
- Magnitude-based Pruning (Global Percentile and Standard Deviation-based Thresholds): This method involves setting a global threshold based on weight magnitudes to prune less significant weights.
- L1-Norm Based Filter Pruning: Pruning filters in convolutional and dense layers using L1-norm as a criterion, with a focus on gradual pruning and fine-tuning.
- Channel Pruning: Implemented to minimize feature map reconstruction error using LASSO regression, adapted for fixed model architecture.

## Content 
- 'Pruning Project Report.pdf': Report on results and comparative analysis of different pruning methods.
- 'CNN_pruning_1.ipynb': Jupyter notebook demonstrating the implementation and analysis of Magnitude-based Pruning and L1-Norm Based Filter Pruning.
- 'CNN_pruning_2.ipynb': Jupyter notebook demonstrating the implementation and analysis of Channel Pruning.

