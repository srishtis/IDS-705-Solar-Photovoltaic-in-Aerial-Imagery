# IDS-705: Solar Photovoltaic in Aerial Imagery
This was for the mid semester Kaggle Project in IDS 705. In this study, we consider the task of comparing two classes of algorithms that automatically detect solar
panels in aerial imagery. One of our approaches combines Gradient Boosting Machines (implemented via the Light GBM algorithm) with Histogram of Oriented Gradient, which lies in the area of classical machine learning algorithms. For the other approach, we use the current state-of-the-art model, EfficientNet with Adversarial Propagation (AdvProp) training scheme, in the class of convolutional neural networks (CNN). Our result shows that the CNN approach substantially outperforms the traditional machine learning approach
in terms of feature extraction and model learnability, yielding superior generalization performance. We also discuss how our modeling approach presents a powerful solution to the challenge of estimating solar power consumption in the United States, thereby having highly scalable applications for both public and private sector industries.

## Data
Our data for this project is comprised of two samples, which we designate as the training and test sets. Our images were stored in the TIFF format. The training dataset has 1500 images. As the test dataset does not have available labels, the models we build either use 10-fold cross validation or create a validation set from the training dataset to assess out-of-sample performance. The training dataset comprises of 505 (33.7%) images having solar panels and the remaining having no solar panels. 

## Methods
We tried the following models:
* Light Gradient Boosting Machine Classifier (with Histogram of Oriented Gradients as features)
* EfficientNet-B4 under AdvProp Training Scheme

## End Deliverable
We submitted a detailed report explaining our approach and results in this project. The report can be found [here]()
