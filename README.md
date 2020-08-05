# Data-Augmentation-Cats-vs-Dogs
Data Augmentation : Adding variations such as rotations, shifts, zooming etc make our classifier much more invariant to changes in our images. Thus making it far more robust.
Take a small dataset and make it much larger! Require much less effort in creating a dataset .
Reduces overfitting due to the increased variety in the training dataset.

Using Kera’s Data Augmentation API : 
Kera’s built-in Data Augmentation API performs a just-in-time augmented image dataset. This means images aren’t created and dumped to a directory (which will be wasteful storage). Instead it generates this dataset during the training process


Cats vs. Dogs Performance with Data Augmentation
● With Data Augmentation after 25 Epochs we got 76.4% Accuracy
● After 25 Epochs without Data Augmentation we got 74.6% Accuracy
