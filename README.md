# Dog Breed Image Classifier

### 🐶 End-to-end Multil-class Dog Breed Classification

This notebook builds an end-to-end multi-class image classifier using TensorFlow 2.x and TensorFlow Hub.

**1. Problem**

Identifying the breed of a dog given an image of a dog.

When I'm sitting at the cafe and I take a photo of a dog, I want to know what breed of dog it is.

**2. Data**

The data we're using is from Kaggle's dog breed identification competition.

https://www.kaggle.com/c/dog-breed-identification/data

**3. Evaluation**
The evaluation is a file with prediction probabilities for each dog breed of each test image.

https://www.kaggle.com/c/dog-breed-identification/overview/evaluation

**4. Features**
Some information about the data:

We're dealing with images (unstructured data) so it's probably best we use deep learning/transfer learning.
There are 120 breeds of dogs (this means there are 120 different classes).
The list of breeds is as follows:

affenpinscher,
afghan_hound,
african_hunting_dog,
airedale,
american_staffordshire_terrier,
appenzeller,
australian_terrier,
basenji,
basset,
beagle, and many more.


There are around 10,000+ images in the training set (these images have labels).
There are around 10,000+ images in the test set (these images have no labels, because we'll want to predict them).

![533FD37D-5B54-416E-A14D-E5BCF8EA8F03](https://user-images.githubusercontent.com/61904667/97219813-8ec81800-17f0-11eb-9435-910f75929ed2.jpeg)

![33D7FF0A-C4B2-4B87-A707-84DF6BE18476](https://user-images.githubusercontent.com/61904667/97219818-91c30880-17f0-11eb-892a-fa67132e5157.jpeg)
