Google Collab Link:https://colab.research.google.com/drive/1qXlU-72bN7PSmph_dNMDUEMSK9huTAEb?usp=sharing


# Fashion-MNIST-Image-Classification

1. What is the Fashion MNIST dataset?

 The Fashion MNIST dataset is a set of grayscale images that shows different types of clothing, such as shirts, shoes, bags, and trousers.
 It contains 60,000 images for training and 10,000 images for testing, with each image sized at 28×28 pixels.
 This dataset is commonly used to help train and test image classification models and is considered a more realistic alternative to the MNIST digit dataset.

2. Why do we normalize image pixel values before training?

Normalizing pixel values (usually from 0–255 to 0–1) helps the model train faster and more stably.
It prevents large input values from dominating the learning process.
Normalization also improves convergence and overall model performance.

3. Why do we normalize image pixel values before training?

 We normalize image pixel values to make training easier and more efficient for the model.
 By scaling the values from 0–255 down to a range between 0 and 1, the model can learn faster and more consistently.
 This process also helps improve accuracy and prevents issues during training.

4. List the layers used in the neural network and their functions.

 The Flatten layer is used to turn the 2D image into a one-dimensional array so it can be processed by the network.
 The Dense (hidden) layer helps the model learn patterns and important features from the data.
 The Output layer gives the final prediction by assigning probabilities to each clothing category.

5. What does an epoch mean in model training?

 An epoch refers to one full cycle where the model sees and learns from the entire training dataset.
 During each epoch, the model adjusts its weights to reduce errors.
 Training for several epochs helps the model improve its predictions over time.

6. Compare the predicted label and actual label for the first test image.

 The actual label shows the true category of the clothing item in the image.
 The predicted label is the category chosen by the model based on what it has learned.
 If both labels are the same, the model made a correct prediction; if not, the prediction is incorrect.

7. What could be done to improve the model’s accuracy?

 The model’s accuracy can be improved by training it for more epochs.
 Adding more layers or neurons can also help the model learn better features.
 Using advanced techniques like dropout, data augmentation, or convolutional neural networks can further boost performance.
