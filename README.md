# Facial Expression
### Objective
Task is to use the feature-level method to combine the facial expression features and audio features. A multi-modal emotion recognition system is constructed to recognize happy versus sadness facial expressions (binary-class problem) by using a classifier training and testing structure.

The original data is based on lab1 and lab2, from ten actors acting happy and sadness behaviors.

### Task 1: 
Subspace-based feature fusion method: In this case, z-score normalization is utilized. Please read “Fusing Gabor and LBP feature sets for kernel-based face recognition” and learn how to use subspace-based feature fusion method for multi-modal system.

### Task 2: 
Based on Task1, use Canonical Correlation Analysis to calculate the correlation coefficient of facial expression and audio features. Finally, use CCA to build a multi-modal emotion recognition system. The method is described in one conference paper “Feature fusion method based on canonical correlation analysis and handwritten character recognition”

### Optional task: 
Use feature-level method (Task 2) on 10-fold cross-validation estimate of the emotion recognition system performance

To produce emotion recognition case, Support Vector Machine (SVM) classifiers are trained. 50 videos from 5 participants are used to train the emotion recognition, use spatiotemporal features. The rest of the data (50 videos) is used to evaluate the performances of the trained recognition systems.
