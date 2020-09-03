TITLE: Predicting Shot Success in Basketball using Deep Learning

To give a clear overview of thesis, here is the abstract:

Abstract

In the field of sports, there has been a huge progress in the prediction tasks using deep neural
networks. In a basketball game, predicting the shot success is very critical (Wright, Silva, &
Kaynar-Kabul, 2016). 3D Convolutional Neural Networks (CNNs) have been among the best
methods to work on huge video datasets till date (Hegde, Agrawal, Yao, & Fletcher, 2018). In
the present study, 3D CNNs have been implemented to predict the shot success in basketball
videos. The two research questions under investigation are:

RQ1: Do CNNs perform better in predicting shot success on a small-scale dataset as compared
to baseline?

RQ2: Does balancing the classes significantly affect the accuracy as compared to the
unbalanced classes in the dataset?

To address RQ1, a subset of the dataset was taken from Ramanathan et al. (2016) where
the shots were labeled as success and failure, and these two classes were unbalanced. The
dataset chosen was comparatively smaller due to time and resource constraints. To train a 3D
CNN model, training model from Tran, Bourdev, Fergus, Torresani, and Paluri (2015) was
referred and changed according to the requirements of the current study. The baseline accuracy
to compare the results of RQ1 was 57.14%. To answer RQ2, classes in the dataset were
manually balanced with an equal number of samples in each class. Afterward, the same
experiment was performed as with the unbalanced classes to compare the results. Baseline
accuracy for the balanced class was 50%.

The results of the RQ1 showed that 3D CNN model accuracy could slightly cross the
baseline with 58.8% as compared to 57.14%. Further, results of RQ2 revealed that balanced
class model accuracy (50%) was equal to its baseline. However, while an input video was
given to in both experiments, there was no significant difference in terms of prediction
probabilities of outcome class. Therefore, from these results, it can be concluded that to predict
well using 3D CNNs, the size of the data matters and it should be large enough for better
training.

Keywords: 3D CNN, shot success, prediction, basketball
