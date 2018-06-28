# Deep-Adaptation-Model-for-Cross-modality-3D-Shape-Retrieval
This repository contains the codes and features used in "Deep Adaptation Model for Cross-modality 3D Shape Retrieval Based on Semantics Preserving Adversarial Learning"

# 1. Features used on the SHREC-ImageNet dataset:
'featPooling5_ResNet50_SHRECImageNet.mat' (Download link: https://drive.google.com/file/d/13CidoSjy18PvaScHFtb-3HUOoanFjqZb/view?usp=sharing): stores features extracted from the 'pooling5' layer of ResNet-50 trained on the SHREC-ImageNet dataset, by using the Importance-Aware and Semantics Embedded Feature Learning method. This file contains the following data:
1. 'FeatOfImg_train': a 76448x2048 matrix. The i-th row is the 2048-dimensional feature of the i-th 2D image for training.
2. 'LabelsOfImg_train': a 76448-dimensinal vector. The i-th element is the class label of the i-th 2D image for training.
3. 'FeatOfImg_test': a 127597x2048 matrix. The j-th row is the 2048-dimensional feature of the j-th 2D image for test.
4. 'LabelsOfImg_test': a 127597-dimensinal vector. The j-th element is the class label of the j-th 2D image for test.
5. 'FeatOfShape': an 8433x2048 matrix. The k-th row is the 2048-dimensional feature of the k-th 3D shape.
6. 'LabelsOfShape': an 8433-dimensinal vector. The k-th element is the class label of the k-th 3D shape.
7. 'Label2Category': stores the correspondence relation between the digital labels and their class categories. For instance, label '1' corresponds to the class 'airplane'.
