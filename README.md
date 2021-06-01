# Ntropy_challenge

I am doing Task 1 from the challenge for Machine learning engineering position. Task is done using Python and Pytorch
In this task, 
1. cut the images in vertically half. 
2. These vertically half images are shuffled and passed to convolutional autoencoder for training.
3. After training, last layer from encoder network, Extracted the embeddings to get latent vector.
4. This latent vector is used with K-nearest neighbor algorithm to find similar images.
5. Similar images are found
6. These similar images then restored with each other to find the original image before cutting it to half.
7. The matching percentage is less.


