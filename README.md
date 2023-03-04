# Audio-Location-Classification-Project
This repository contains two machine learning pipelines which takes audio clips as input and predicts whether the recording was made inside or outside. 
## Basic Model - 
The Basic Model contains a machine learning pipeline that takes an audio segment as input and predicts whether it was recorded indoors or outdoors. The pipeline was built using the MLEnd London Sounds dataset and consists of the following stages:

A. Loading the Dataset
The .wav files from the MLEnd London Sounds dataset were loaded using the provided link.

B. Intermediate Stages
Feature Extraction - The audio features were extracted using techniques such as MFCC, Spectral Centroid, Spectral Bandwidth, Spectral Contrast, and Chromagram for each note in the .wav files.

Training Analysis - The training accuracy of the model was analyzed using cross-validation scores. Confusion matrix analysis was used to calculate precision, recall, and accuracy for each class.

Validation Analysis - The validation accuracy of the model was calculated. Confusion matrix analysis was used to calculate precision, recall, and accuracy for each class.

C. Conclusion
Based on the results of the analysis, a conclusion was made about the model's ability to accurately classify indoor and outdoor sounds.

For more information about the pipeline and its implementation, please refer to the code in this repository.

##Advanced Model - 
This repository contains a machine learning pipeline that predicts the area where a sound recording took place using the MLEndLS dataset. The pipeline classifies recordings into 6 different areas and creates a confusion matrix to analyze precision, recall, and accuracy for each class. The most dominant class is also determined.

A. Loading the Dataset
The .wav files from the MLEndLS dataset were loaded using the provided link.

B. Intermediate Stages
Feature Extraction - The audio features were extracted using techniques such as MFCC, Spectral Centroid, Spectral Bandwidth, Spectral Contrast, and Chromagram for each note in the .wav files.

Training Analysis - The training accuracy of the model was analyzed using cross-validation scores. Confusion matrix analysis was used to calculate precision, recall, and accuracy for each class.

Validation Analysis - The validation accuracy of the model was calculated. Confusion matrix analysis was used to calculate precision, recall, and accuracy for each class.

C. Conclusion
Based on the results of the analysis, a conclusion was made about the model's ability to accurately classify sound recordings into their respective areas. The most dominant class was also identified.

For more information about the pipeline and its implementation, please refer to the code in this repository.
