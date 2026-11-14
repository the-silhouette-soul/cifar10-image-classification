CIFAR-10 Image Classification Using CNN

About the Project

I built a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset into 10 different categories.
The project uses TensorFlow and Keras. It covers loading the dataset, preparing the images, building and training the model, and checking how well it performs.

Dataset

The CIFAR-10 dataset contains:

- 60,000 colour images
- Image size of 32 × 32 pixels
- 10 different classes
- 50,000 training images
- 10,000 testing images

Tools and Libraries

- Python
- TensorFlow and Keras
- NumPy
- Matplotlib
- Scikit-learn

Model

I used a CNN with:

- Two convolutional layers (32 and 64 filters)
- Two max-pooling layers
- A flatten layer
- A dense layer with 64 neurons
- An output layer with 10 classes using softmax

Training Details

- Optimizer: Adam
- Loss function: Sparse Categorical Crossentropy
- Epochs: 15
- Batch size: 64
- Validation split: 10%

Results

- Test Accuracy: 66.60%
- Test Loss: 1.1455
- Macro F1-score: 0.66

I evaluated the model using test accuracy, a classification report, a confusion matrix, and sample predictions.

What I Observed

- The model was able to learn useful features from the images.
- Training accuracy continued to increase, but validation performance started to decline in later epochs. This suggests some overfitting.
- The model performed better on some classes than others.
- Cat classification was particularly challenging, with a recall of 0.33.

Future Improvements

- Try data augmentation.
- Experiment with different CNN architectures.
- Use regularisation to reduce overfitting.
- Experiment with different training settings.

How to Run

1. Open the notebook using Google Colab.
2. Run all cells.
3. The CIFAR-10 dataset will be downloaded automatically through Keras.
4. View the training graphs, evaluation results, and predictions.

Files

- "cifar10_image_classification_final.ipynb" – Project notebook.
