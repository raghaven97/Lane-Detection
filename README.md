# Lane-Detection
Lane Detection on roads for Autonomous Driving

## Overview
When we drive a car, our eyes will look for different traffic signs, rules. How about automating this using car's camera. THis is exactly what we are trying to achieve here. Car will detect the lanes and try to maintain the lane discipline.

To train the model an image/video has to go through various processes.
  1. An image has to be converted to Grayscale
  2. Reduce the noise by using Gaussian Blur
  3. Detect the edges by using Canny method of OpenCV
  4. Select the region of interest by masking the image
  5. Use Hough Transform to merge images
  6. Optimize the Algorithm
