# API Breast Cancer Tumor Predictor (HCS Bootcamp 2)

### Sun-Jung Yum
### October 24, 2019

This API takes several inputs about a tumor (i.e. clump thickness, cell size/shape, mitosis, etc.) to classify a given breast cancer tumor as benign or malignant. The 569 instances from 1992 were split into two groups in order to train the API on one group and test it on another in order to avoid overfitting. It uses machine learning in Python using scikit-learn to implement the K Nearest Neighbors algorithm.

This code was largely based off of the Iris Classification API that was presented during the HCS Bootcamp 2. The data can be found here: https://www.mldata.io/dataset-details/breast_cancer/