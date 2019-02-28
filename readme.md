# Image Features and Homography




#### 1. Original Images

<p align="center">
  <img height="300" width="400" src="https://raw.githubusercontent.com/rohangupta/homography/master/data/mountain1.jpg"> 
  <img height="300" width="400" src="https://raw.githubusercontent.com/rohangupta/homography/master/data/mountain2.jpg"><br>
</p>
<br>

#### 2. Extracting SIFT features and drawing the keypoints   

<p align="center">
  <img height="300" width="400" src="https://raw.githubusercontent.com/rohangupta/homography/master/task1_sift1.jpg"> 
  <img height="300" width="400" src="https://raw.githubusercontent.com/rohangupta/homography/master/task1_sift2.jpg"><br>
</p>
<br>

#### 3. Matching the keypoints using k-nearest neighbour (k=2) algorithm. Filtering and displaying the good matches (m.distance &lt; 0.75 * n.distance, where m is the first match and n is the second match). 

<p align="center">
  <img src="https://raw.githubusercontent.com/rohangupta/homography/master/task1_matches_knn.jpg">
</p>
<br>

#### 4. Computing the homography matrix H (with RANSAC) from the above two images

<p align="center">
  [[ 1.58799966e+00 -2.91541838e-01 -3.95539425e+02]<br>
  [ 4.48199617e-01  1.43139761e+00 -1.90370131e+02]<br>
  [ 1.20864262e-03 -5.94920214e-05  1.00000000e+00]]
</p>
<br>

#### 4. Displaying 10 random matches using only inliers
 
<p align="center">
  <img src="https://raw.githubusercontent.com/rohangupta/homography/master/task1_matches.jpg">
</p>
<br>

#### 5. Warping the first image to the second image using homography matrix H.

<p align="center">
  <img src="https://raw.githubusercontent.com/rohangupta/homography/master/task1_pano.jpg">
</p>
<br>