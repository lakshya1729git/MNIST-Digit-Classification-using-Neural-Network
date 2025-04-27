MNIST Digit Classification using Neural Network

Project Overview -->

This project implements a neural network model for classifying handwritten digits from the MNIST dataset.
The workflow includes data preprocessing, neural network design, training, evaluation, and performance visualization.
The aim is to demonstrate the application of deep learning techniques for image classification tasks.

Approach-->
Loaded and preprocessed the MNIST dataset (normalization, reshaping).

Built a fully connected neural network using Keras Sequential API.

Used ReLU activation for hidden layers and Softmax activation for the output layer.

Compiled the model with Adam optimizer and Sparse Categorical Crossentropy loss.

Trained and validated the model to monitor performance.

Visualized training and validation accuracy and loss across epochs.


Libraries and Dependencies-->
Python 3.x
TensorFlow 2.x - keras
NumPy
Matplotlib
seaborn 
cv2

Results-->
Achieved high classification accuracy on the MNIST test dataset.
Visualized training and validation performance across epochs to ensure model stability and avoid overfitting.
Sample prediction results can be added for visualization (optional).


Conclusion-->
This project successfully demonstrates a neural network-based approach for solving a classic image classification problem.
It provides a strong foundation for extending to more complex architectures such as CNNs for further improvement.
