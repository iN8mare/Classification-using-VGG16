# Classification-using-VGG16 (Transfer Learning)
Classification of dog and cats using VGG16. (https://www.kaggle.com/datasets/salader/dogs-vs-cats) </br>
This repo has 2 notebooks - 
1. VGG16 feature extraction: here, I used the VGG16 model's convolutional layer with weights corresponding to ImageNet data. I modified the fully connected layer to predict the image as dog or cat and further used data augmentation using Keras Image Data Generator to improve cross-val accuracy (about 92%).
2. VGG16 fine tuning: here, I used VGG16 model's convolutional layer except the last layer. I fine tuned the last layer and the fully conncted layer to classify the image as got about 93% cross-val accuracy for the same.
