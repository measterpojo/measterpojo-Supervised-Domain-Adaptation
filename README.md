DANN-Supervised-Domain-Adaptation
Introduction
Weakly Supervised Domain Adaptation (WSDA) is an exciting area of research that aims to improve the performance of machine learning models when there is a lack of fully labeled data in the target domain. Here are some key points and recent advancements in this field:

Domain adaptation - The process of transferring knowledge from a source domain to a target domain
Weak adaptation - Using weak labels, such as noisy or incomplete annotations to train models
Domain-Adversarial Neural Networks (DANN)

Domain-Adversarial Neural Networks (DANN) can be adapted for weakly supervised. DANN is a popular approach for domain adaptation that uses adversarial training to align feature distributions between the source and target domains. Here's a brief overview of how DANN can be applied in weakly supervised settings:

Feature Extractor: Extracts features from the input data.
Label Predictor: Predicts labels based on the extracted features.
Domain Classifier: Predicts the domain of the input data (source or target).
Applications

Semantic Segmentation - Improving the accuracy of segmenting images into meaningful parts using weak labels.

Object Detection - Enhancing object detection models in target domains with limited annotations.

Datasets

Office-31 : The Office-31 dataset consists of 31 object categories commonly found in office settings. This dataset includes images from three domains. In this experiment we are only going to use 2 out of the 3
