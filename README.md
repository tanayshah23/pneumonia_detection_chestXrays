# Pneumonia Detection Using Chest X-Rays

### Dataset:
1. Download the dataset from https://data.mendeley.com/datasets/rscbjbr9sj/2.
2. Unzip and paste the complete folder in the same directory as of the jupyter notebook.

### Approach:
1. Image Pre-processing<br />
    a. Image Enhancement using Laplacian Filter<br />
    b. Histogram Equilization<br />
    c. Image Restoration using Median Filter<br />
    d. Power Law Transformation.
2. Segmentation using Thresholding
3. Feature Extraction [Contrast, Energy, Dissimilarity and Homogeneity]
4. Applying Machine Learning models on these features
