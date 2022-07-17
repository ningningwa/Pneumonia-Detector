# Pneumonia-Detector

Pneumonia is an infection of one or both of the lungs caused by bacteria, viruses, or fungi. In medical image diagnosis, pneumonia often
presents itself as increased opacity in chest X-Rays. In order to improve
the efficiency and accuracy of identifying pneumonia from chest X-Rays,
various models have been proposed for this task. In this work, we examine
multiple non-deep and deep learning models for classifying chest X-Ray
images. We first feed pre-processed data to a family of traditional machine learning models, including SVM, Random Forest, Gradient Boosting, etc. Then, we compare the results of several deep learning models,
which include a self-designed CNN, AlexNet, and ResNet18. While most
previous work focuses on CNN-based models, we introduce Swin Transformer, which is a state-of-the-art computer vision model that leverages
ideas like patch embedding. Statistical results obtained demonstrate that
Swin Transformer can generate significantly better classification results
for chest X-Rays than CNN-based models
