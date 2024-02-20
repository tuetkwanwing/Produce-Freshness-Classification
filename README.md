# Produce Freshness Classification Using Neural Network with a Pre-trained Model Base VGG16

The purpose of this project is to predict whether a fruit or vegetable is fresh given the picture of it. The predictor would be sets of images for different kinds of fruits and vegetables and the labels would be binary. The labels can be understood as “fresh” or “stale”. Specifically, for images with more than one fruit or vegetable, our ideal solution would be to first recognize how many items are included, then separating them and detecting the freshness one by one, and finally producing several classification labels for the given image.

See [Produce Freshness Classification Project Proposal](https://github.com/tuetkwanwing/Produce-Freshness-Classification/blob/main/Produce%20Freshness%20Classification.pdf) for more information on the project's background, objective, data preparation and some sample pictures.

This Jupyter Notebook [Produce_freshness_classification_Project_Tuet.ipynb](https://github.com/tuetkwanwing/Produce-Freshness-Classification/blob/main/Produce_freshness_classification_Project_Tuet.ipynb) concludes the session of me processing image data from Google Cloud Files, performing data cleansing and transformation, constructing a neural network with a pre-trained model base VGG16 with its training history, as well as applying a [LIME Image Explainer](https://lime-ml.readthedocs.io/en/latest/lime.html) to explain the outputs/results of my neural network.



