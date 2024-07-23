# EM-VAE

EM-VAE implements the EM algorithm in the decoder part and performs model training.It uses a decoder that clusters latent variables with a Gaussian Mixture Model and updates the cluster parameters using the EM algorithm.
The aim is to improve the clustering performance of the latent space by incorporating the EM algorithm into the decoder part of the VAE.
Additionally, we want to focus on the stability and reconstruction quality of the VAE.


![image](https://github.com/user-attachments/assets/b99f5477-b423-42c1-b459-cfe1cf66bb48)

This image is from a VAE trained on the Fashion MNIST dataset. From top to bottom, it shows the labels, VAE, and EM-VAE. Visually, it appears that the EM-VAE has slightly higher accuracy.









