# Dimensionality-Reduction-techniques-and-MNIST-task

Using Principal Components Analyses (PCA) and t-Distributed Stochastic Neighbor Embedding (t-SNE) on Fashion-MNIST dataset. Fashion-MNIST is a dataset with 60,000 training and 10,000 test images from Zalando articles. Each 28x28 grayscale image corresponds to one of 10 categories. (Source: https://github.com/zalandoresearch/fashion-mnist) 

- Visualise the data and verify each of the 10 classes has 6,000 items. Create a function to display an image from the training set using its index. For efficiency, use only the first 5,000 samples for initial tests instead of all 60,000.
- Verify that the new subset contains about 500 samples from each fashion category.
- What happens if we ignore principal components and simply pick two of the 784 dimensions to plot our data and labels?
- Compare using all 784 dimensions. How does this look compared to the first visualization? How does using 35 dimensions stack up against all 784?
- Experiment with different numbers of principal components (PCs), like just the first 5 to 10, to see how it affects visualisation.
