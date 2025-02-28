**1. What are the common distance metrics used in distance-based classification algorithms?**

Common distance metrics in distance-based classification algorithms include Chebyshev distance, Bray-Curtis distance, Hamming distance, Canberra distance, and Jaccard similarity. These metrics evaluate the similarity or dissimilarity between data points depending on their characteristics and context of application.

**2. What are some real-world applications of distance-based classification algorithms?**

Distance-based classification algorithms are widely applied in fraud detection, speech recognition, biometric authentication, DNA sequencing, and geospatial analysis. For instance, KNN is useful in fingerprint recognition systems where an unknown fingerprint is classified based on its similarity to stored fingerprints.

**3. Explain various distance metrics.**

- **Chebyshev Distance**: Measures the greatest absolute difference between coordinates of two points.
- **Bray-Curtis Distance**: Evaluates dissimilarity based on the sum of absolute differences over the sum of values.
- **Hamming Distance**: Used for categorical data, counting the number of differing bits between two binary strings.
- **Canberra Distance**: Computes a weighted version of Manhattan distance, giving more weight to smaller values.
- **Jaccard Similarity**: Compares the intersection and union of two sets, commonly used in clustering and classification.

**4. What is the role of cross-validation in model performance?**

Cross-validation evaluates a model’s effectiveness by partitioning the dataset into different subsets for training and testing multiple times. It mitigates issues of overfitting by ensuring the model performs consistently across various data splits, leading to better generalization.

**5. Explain variance and bias in terms of KNN?**

In KNN, selecting a very small K value results in low bias but high variance, meaning the model closely follows training data and is sensitive to noise. Conversely, a very large K value leads to high bias and low variance, making the model more stable but less flexible. An optimal K balances both to ensure reliable performance.
