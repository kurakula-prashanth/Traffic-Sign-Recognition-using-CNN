# Traffic-Sign-Recognition-using-CNN

# Here we have taken GTSRB dataset and implemented CNN and FCN and trained the model to do the image recognition.

A CNN is a type of deep learning model that is particularly well-suited for image recognition tasks. The architecture of a CNN consists of multiple layers of convolutional, max-pooling, dropout, dense, flatten ,batch normalisation.

In the second model we use a FCN with multiple layers of flatten, dense, batch normalisation and dropout.

In our approach, the input to the network was an image of a traffic sign resized to 30x30 pixels. The output of the network was a vector of probabilities for each of the 43 classes of traffic signs in the GTSRB dataset. The model was trained using the Adam optimization algorithm with a cross-entropy loss function. 

# Results

# Train Data Model Graph
![image](https://github.com/user-attachments/assets/37c118ab-f487-4d78-9808-12163bb63004)


# Test Data Accuracy
![image](https://github.com/user-attachments/assets/2f8a1b00-119a-457e-9737-2a06c3389a96)

![image](https://github.com/user-attachments/assets/7970e5f9-363c-4efe-a164-2467ce37c12a)
