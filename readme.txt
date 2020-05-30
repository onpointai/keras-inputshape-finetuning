https://www.pyimagesearch.com/2019/06/24/change-input-shape-dimensions-for-fine-tuning-with-keras/

Change input shape dimensions for fine-tuning with Keras

Data: dogs_vs_cats_small moved to /Volumes/DATA

cwd: /Users/dexterdsilva/Documents/Developer/MachineLearning/pyimage/keras-input-shape-to-do

ln -s /Volumes/DATA/dogs_vs_cats_small/ ./data


by Adrian Rosebrock on June 24, 2019 in Deep Learning, Keras, Tutorials

Consider the fact that CNNs reduce volume dimensions via two methods:

Pooling (such as max-pooling in VGG16)
Strided convolutions (such as in ResNet)

