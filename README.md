# Autoencoders and Variational Autoencoders

Autoencoders and variational autoencoders using the dataset MNIST.
We apply those following techniques:

* PCA (principal component analysis), which is one of the fundamental tools in Statistics and Machine Learning. It is used widely to reduce the dimensionality of the data to obtain combinations of features that optimize to retain maximum variance in the data. We use PCA along with k-Means clustering in this task as the first Unsupervised model.

* Dimensionality reduction using an Autoencoder instead of PCA as autoencoders can be interpreted to be non-linear PCAs.

* Dimensionality reduction using Variational Autoencoders which allows us to regulare the latent space using the latent representations to synthesize new data. 

Latent space of VAE for the first 5 digits (0,1,2,3,4)

![alt text](images/latent_vae.jpg?raw=true)

Synthesize new data by picking elements in the latente space

![alt text](images/synthetized_data.jpg?raw=true)
