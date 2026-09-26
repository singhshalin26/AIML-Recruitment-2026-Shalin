 AIML Recruitment 2026 – Shalin Singh

 1. Candidate Details

Name: Shalin Singh
Course: B.Tech Computer Science and Engineering
University: SRM University

 2. Tasks Completed

Task 2: Neural Network – MNIST Digit Classification

 3. Problem Statement

The objective of this task is to build a simple neural network that can classify handwritten digit images from 0 to 9 using the MNIST dataset.
The project focuses on understanding the basic steps involved in building a neural network, including data preprocessing, model building, activation functions, training, evaluation, and comparing different model architectures.

 4. Approach
The MNIST dataset was loaded using TensorFlow/Keras. The images are 28 × 28 grayscale images containing handwritten digits from 0 to 9.
The following steps were performed:
1. Loaded and inspected the MNIST dataset.
2. Visualized sample handwritten digit images.
3. Normalized pixel values from 0–255 to a range of 0–1.
4. Used a Flatten layer to convert each 28 × 28 image into 784 input values.
5. Built a simple neural network using Dense layers.
6. Used ReLU as the activation function in the hidden layer.
7. Used Softmax in the output layer for the 10 digit classes.
8. Trained the model using the Adam optimizer.
9. Evaluated the model using test accuracy and test loss.
10. Created a confusion matrix to analyse the predictions.
11. Calculated precision, recall, and F1-score.
12. Built a second model with a different architecture and compared its performance with the original model.

 5. Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab
* Jupyter Notebook
* GitHub

 6. Results

The neural network was trained and evaluated using the MNIST test dataset.
The project includes:
* Training and validation accuracy
* Training and validation loss
* Test accuracy and test loss
* Confusion matrix
* Precision, recall, and F1-score
* Sample predictions
* Comparison between the original and modified neural network

The complete results and visualizations are available in `MNIST_Neural_Network.ipynb`.

 7. Key Learnings
1. Learned how to load and preprocess image data for a machine-learning model.
2. Understood the basic structure of a neural network and the role of its layers.
3. Learned how ReLU and Softmax activation functions work.
4. Learned how to train and evaluate a classification model.
5. Understood how a confusion matrix can be used to analyse classification errors.
6. Learned how changing the neural network architecture can affect model performance.

 8. Challenges

One challenge was understanding how changing the neural network architecture affects its performance. I addressed this by creating a second model with a different number of hidden layers and neurons and comparing its results with the original model.

Another challenge was understanding why image pixel values need to be normalized before training. By converting the values from 0–255 to 0–1, the input data becomes easier for the neural network to work with during training.

 Project Structure
```text
AIML-Recruitment-2026-Shalin
│
├── README.md
└── MNIST_Neural_Network.ipynb
---

 Conclusion
This project helped me understand the basic workflow of building a neural-network classification model, from preprocessing the dataset to training, evaluating, and experimenting with different model architectures.
