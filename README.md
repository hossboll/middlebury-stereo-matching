# Middlebury Stereo Matching
### The objective of this project is to assess the quality of the disparity maps generated by window matching in computer vision.  

A stereo pair of rectified images is used, and the objective is to calculate the disparity for each pixel (x, y) in the image, defined as the one for which a cost C0(x, y, d) is minimal. Two different cost criteria are tested: SSD in a window using Euclidean distance in the CIELAB color space, and a robust error function based on SSD. The results are evaluated quantitatively using the Middlebury benchmark, with RMS error and percent of bad pixels being the metrics used.
This is the second implementation assignment of the Computer Vision Fundamentals course in the UFRGS Computer Science graduate program. 
