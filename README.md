
![Simple inception](https://github.com/skjdaniel/uva-deep-learning/blob/master/notebooks/simple-inception.ipynb)

Implement a simple Inception-based CNN using Pytorch Lightning for CIFAR10 classification.
- Import `torch`, `pytorch_lightning`, etc.
- Download CIFAR10 train set and calculate mean and std for each channel.
- Create train and test transforms. Split train set into train and val sets. Create train, val, and test loaders.
Check the normalization.
- Create the `InceptionBlock` class, the `SimpleInception` model (with ~110,000 params), and the
`LightningModule` class `CIFARModule`.
- Define a function to train and evaluate the model. Use Lightning's `ModelCheckpoint` to
return the model with the best one-epoch val accuracy.
- Train model. (Very briefly. Just a few epochs, and limiting train/val/test batches.) 
 
