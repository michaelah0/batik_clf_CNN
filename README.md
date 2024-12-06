# batik_clf_CNN
Batik motif classification with CNN without transfer learning

The data link:
https://drive.google.com/drive/folders/1BU99yAQYL9EKAyEZxDBafsAcGzQ4csTC?usp=sharing

Batik motif classification uses convolutional neural network (CNN) to classify batik motif into one of the following classes:
1. Gajah Oling
2. Kawung
3. Mega Mendung
4. Parang
5. Pucuk Rebung

The original scrapped data is augmented until the total count for each class is around 1000.
There are two CNN models, single-branch model and multi-branch model. The multi-branch model was created because the single-branch model was unable to perform well with 64% validation accuracy. The multi-branch model fixed that issue and managed to perform with 92% accuracy on validation data.
