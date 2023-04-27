<h1>Covid-19 Detection</h1>
Use convolutional neural networks to detect COVID-19

Traditional neural networks are not optimized for image analysis tasks. They are not able to effectively handle the high-dimensional nature of visual data. This is the main limitation of the Deep Neural Network we reviewed in the Outfit Classifier.

Convolutional Neural Networks (CNNs) are a type of neural network architecture that are particularly well-suited for image and video analysis tasks. They are designed to identify patterns and features within visual data by applying convolutional filters to the input image.

CNNs were designed to address this limitation by incorporating several key features, including:

* Convolutional layers: these layers apply a set of filters (also known as kernels) to the input image, allowing the network to detect specific features, such as edges or textures, in different parts of the image.

* Pooling layers: a particular case of convolution - these layers downsample the output of the convolutional layers, reducing the dimensionality of the data and making it easier to process.

Today we will train a Convolutional Neural Network with a bunch of X-rays in order to detect COVID-19.
