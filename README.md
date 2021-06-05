# EVA6-S5-CodingDrilldown

##Code 1
Target - Achieve basic model skeleton with <10000 parameters.

Results -
1.  Model created has 9294 parameters.
2.  Max validation accuracy is 99.23%, with respective training accuracy being 99.49%.

Analysis -
1.  Model is able to learn properly.
2.  The difference between training and validation accuracies points to overfitting. Regularization can be added to avoid overfitting, while increasing validation accuracy.



##Code 2
Target - Reduce overfitting by adding regularization and increase validation accuracy.

Results -
1.  Difference between training and validation accuracy is negative most times (implying regularization is making training harder, and forcing parameters to learn better). Therefore, model is able to maintain 99.20%+ validation accuracy consistently.
2.  Max validation accuracy is 99.25%, with respective training accuracy being 99.16%.

Analysis -
1.  Model is being forced to learn better with regularization, pushing validation accuracy.
2.  Augmentation can be used to compensate of different orientations of images in dataset.




##Code 3
Target - Add augmentation to further increase validation accuracy.

Results -
1.  Augmentation further makes learning difficult, keeping training accuracy smaller than validation accuracy for all epochs.
2.  Max validation accuracy is 99.42%, with respective training accuracy being 99.06%.

Analysis -
1.  The validation accuracy is consistent in last epochs.
2.  The validation accuracy keeps oscillating. Need to devise a learning rate strategy.
