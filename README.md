# Goal
 In this project, we create and train a small GAN from scratch on the MNIST dataset. We  display a few generated images as training progresses and inspect them visually. 
 The goal is to generate new images that are similar to the ones in the dataset We  also implement the idea of ’Inception scores’ to evaluate our model. 

 # Dataset
 The MNIST dataset is a collection of handwritten digits that is commonly used as a benchmark dataset for image classification tasks. It consists of 60,000 training images and 10,000 testing images, each of which is a grayscale image of size 28x28 pixels. The images are labeled with the corresponding digit from 0 to 9. We choose to work with the MNIST dataset which is a popular choice for GANs because it is relatively small and easy to work with, making it a good starting point for learning about GANs.

 # Result
 The quality of the generated images improved significantly over time. At the beginning of training, the generated images were mostly noise with no discernible features. However, as the model was trained for more epochs, the generated images became more realistic and began to resemble the training data.

 The Inception score increased steadily over time, indicating that the quality and diversity of the generated images improved as the model was trained for more epochs. At the start of training, the Inception scores were low (1.0049), indicating that the generated sam- ples were dissimilar to the training data. However, as training progressed, the Inception scores increased, indicating that the generated samples were becoming more similar to the training data, and become 5.7 at epoch 500. This is consistent with our visual inspection of the gener- ated images, which also showed a clear improvement over time.
Overall, these results suggest that the GAN model was able to generate high-quality images that closely resembled the training data, and that the model continued to improve as it was trained for more epochs.



 The notebook is well documented and commented. Just follow each step and read the comment after each cell.
