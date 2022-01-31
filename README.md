# GMM
Gaussian Mixture Modelling based clustering to segment a colored image


An image was selected at random, and then the following tasks were performed:
1. Preprocessing phase   
      A 5 dimensional feature vector was generated for each pixel of the image, in which 
      a. Append row index, column index, red green blue value for each pixel into a raw feature vector
      b. Normalise each feature entry individually to the interval [0,1]
2. Fit a Gaussian Mixture Model (GMM) to these normalized feature vectors representing the image pixels. (10 Fold cross validation for model order selection & Maximum Likelihood Parameter Estimation for fitting the GMM).
3. Identification of the best GMM for the feature vectors and assigning the most likely component label for each pixel.
4. Presentation of original image and GMM based segmentation labels.

