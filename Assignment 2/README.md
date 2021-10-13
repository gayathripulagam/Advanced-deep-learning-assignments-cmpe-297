# Perceiver and Perceiver_IO

**Image classification using Perceiver for CIFAR-10 data**

* Perceiver_example notebook showcases image classification on CIFAR-10 dataset using Perceiver model. Because of a long training time (close to 10 hours per epoch), I used a subset of the CIFAR-10 data (5000 images instead of 50000). The overall training time was 10 hours for 5 epochs and the colab's runtime disconnected toward the end of the last epoch. 
* The training accuracy and the val accuracy increased through the epochs, while the training loss and val loss reduced with each epoch

**Masked Language Modelling using Perceiver_IO**

* Used a random text sentence from wikipedia and masked a particular word. The model predicted the masked word correctly. 
* For future work, it would be interesting to observe the results on a large text dataset

**References**

1. https://keras.io/examples/vision/perceiver_image_classification/
2. https://github.com/2796gaurav/code_examples/tree/main/Perceiver
3. https://medium.com/analytics-vidhya/perceiver-io-a-general-architecture-for-structured-inputs-outputs-4ad669315e7f
