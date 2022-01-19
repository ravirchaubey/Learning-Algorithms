### Problem Statement : Dominant Colour Extraction

> As you can see in this figure, we need to extract dominant color from given image.

![](https://miro.medium.com/max/874/1*2WkkuIeL6EWZNY-uFEcSJA.png)

#### Methodology

1. Read Image and convert it in to a tidy format to work with.

2. Using Elbow method for `KMeasn Clustering Algorithm` **(Unsupervised Learning)** , Find optimal number of clusters of given image.

3. Recreate model with optimal number of Cluster.

4. Use Cluster center (RGB) value to show dominant color.

#### Tools Used

1. Python
2. SciPy
3. Unsupervised Learning

[Open Notebook Here](https://github.com/ravichaubey/Learning-Algorithms/tree/main/Unsupervised%20Learning/2-Dominant%20Colour%20Extraction)
