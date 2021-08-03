# Data Augmentation

In this repo, I use modified LeNet architecture to build classification model for `simpsons dataset`. 

<p align="center">
    <img src="doc/simpsons.png" />
</p>

The model is trained separately on two different datasets:
- The original one.
- The extended one using data augmentation technique.

Training the model using the original dataset led to overfitting, since the model has huge number of trainable parameters.

<p align="center">
    <img src="doc/model1_accuracy.png" />
    <img src="doc/model1_loss.png" />
</p>

Using the augmented datasets, more robust model with impressive results were achieved.

<p align="center">
    <img src="doc/model2_accuracy.png" />
    <img src="doc/model2_loss.png" />
</p>