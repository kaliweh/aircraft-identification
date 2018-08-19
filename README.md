# Identification of Aircraft

### Problem Statement:
Aircraft manufacturer Identification given the aircraft image.

### Dataset Used:
The dataset was extracted from the Fine-Grained Visual Classification of Aircraft (FGVC-Aircraft) project.

### Dataset Project Website: 
http://www.robots.ox.ac.uk/~vgg/data/fgvc-aircraft/ 

### Dataset Description:
The dataset contains 10000 images of aircraft. The Aircraft models are organized in a four-levels hierarchy. The four levels, from finer to coarser, are: Model, e.g. Boeing 737-76J. Variant, e.g. Boeing 737-700. Family, e.g. Boeing 737. The dataset comprises 70 different families and Manufacturer, e.g. Boeing. The dataset comprises 41 different manufacturers.

### Approach:
Utilize Keras/Tensorflow backend to build a Sequential Convolutional Neural Network (CNN) model that can classify the aircraft manufacturer. The model was designed and trained to differentiate between two different classes [Boeing and Airbus]

### Challenges:
Aircrafts are nearly visually indistinguishable and requires a large neural network and computational resources to capture the aircraft features.

### Solution:
Utilize image augmentation techniques to increase the classification accuracy.

### Results:
The average validation accuracy for the last 5 training epochs of 50 epochs was 80.08%.
