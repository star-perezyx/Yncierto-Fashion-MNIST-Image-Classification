# Yncierto-Fashion-MNIST-Image-Classification

Google Colab Link:<a href="https://colab.research.google.com/drive/1P9FGrXTI1HJX3eIRUlz461t79nE-8BZJ?usp=sharing">Click Here👈</a>

Questions: (February 8, 2026)
1. What is the Fashion MNIST dataset?
     Ans: Fashion-MNIST is a dataset of 70,000 grayscale 28×28 images of clothing in 10 categories, used for training and testing image classification models.

2. Why do we normalize image pixel values before training?
     Ans: We normalize pixel values to 0–1 to make training faster, more stable, and improve model performance.

3. List the layers used in the neural network and their functions.
    Ans: Flatten: converts 2D image to 1D array
         Dense (hidden, ReLU): learns features
         Dense (output): produces class logits
         Softmax: converts logits to probabilities
   
5. What does an epoch mean in model training?
     Ans: An epoch is one complete pass through the entire training dataset during model training.

6. Compare the predicted label and actual label for the first test image.
     Ans: For the first test image, the model predicted Ankle boot and the actual label is Ankle boot.

9. What could be done to improve the model’s accuracy?
     Ans: The model’s accuracy can be improved by adding more layers or neurons, using convolutional layers (CNN), increasing training epochs, tuning hyperparameters, or applying data augmentation.


Tasks Enhancement:
1. Change the number of neurons in the hidden layer (e.g., 64 or 256) and retrain the model.
   64 = Test accuracy: 0.8174999952316284
   256 = Test accuracy: 0.8220999836921692
   
3. Increase the number of epochs and observe changes in accuracy.
   Test accuracy after more epochs: 0.8349999785423279
   
5. Add another hidden layer and compare the results.
   Test accuracy with 2 hidden layers: 0.8503999710083008
