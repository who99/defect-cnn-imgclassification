# Convolutional Neural Networks (CNN)

CNN: type of neural network used for image classification, recognition, etc.

* Simple image classification using CNN

  <img width="481" alt="cnn_1" src="https://user-images.githubusercontent.com/78089713/106094608-a27b7580-6175-11eb-8fa2-19ca90fc2137.png">

* One example of CNN, how the network is composed.

  <img width="512" alt="cnn_2" src="https://user-images.githubusercontent.com/78089713/106094658-b7f09f80-6175-11eb-8ff7-fab4ea288241.PNG">

# Model Explanation

### Multi-class Image Classifiation using CNN

###### → This model is made to classify defects of different types (in this case, 4) of a company's product. Due to confidentiality, the dataset cannot be revealed. 

* Training set: 70985, validation set : 7888 (total : 78873)
* Test set: 938
* Input shape: (200, 200, 3)
* Conv2D: 4 layers
* Optimizer: Stochastic Gradient Descent (SGD)
* Loss: categorical crossentropy
* Learning rate: exponential decay
  - Image of this model's network
  <img width="602" alt="model_1" src="https://user-images.githubusercontent.com/78089713/106098086-c641ba00-617b-11eb-8b5e-ddd3e4c3b675.PNG">
  
  - Importance of choosing a decent learning rate
  : When the accuracy and loss do not converge, changing the learning rate can help. Instead of using a constant learning rate, it is possible to change the learning rate according to the epoch by using the learning rate scheduler. In this case, the initial value of the learning rate was 0.00001 and exponential decay was used for scheduling.
  
  
  <img width="613" alt="model_2" src="https://user-images.githubusercontent.com/78089713/106094877-22094480-6176-11eb-8f9c-168515604ec1.PNG">

###### * note: model still in progress
