# Created By - Piyush Dwivedi 
Connect me - https://www.linkedin.com/in/piyushdwivedi-/

Email Address- dwivedipiyush9754@gmail.com

# Output Video - 

https://user-images.githubusercontent.com/96904569/228859853-f5e3bd5d-60e3-4c68-a625-8e2e9abbafdd.mp4


# Library used and their work

# #OpenCv
Image/video I/O, processing, display (core, imgproc, highgui)

Object/feature detection (objdetect, features2d, nonfree)

Geometry-based monocular or stereo computer vision (calib3d, stitching, videostab)

# #Numpy 
An array object of arbitrary homogeneous items

Fast mathematical operations over arrays

Linear Algebra, Fourier Transforms, Random Number Generation

# #Matplotlib
Plotting library

data visualization and graphical plotting library for Python

its numerical extension NumPy

# #Sckit-image
Image processing

# #Hog
Histogram of Oriented Gradients

# Information about the project :
In this Porject i make a plot of the Histogram of Oriented Gradients (HOG) feature descriptor with visualization of the HOG feature vector, also i make a plot of the HOG feature vector for a given image.

# Function used in this project :
1. hog() : This function is used to compute the Histogram of Oriented Gradients (HOG) feature descriptor with visualization of the HOG feature vector.
2. imread() : This function is used to read an image from the specified file.
3. imshow() : This function is used to display an image in a window.
4. waitKey() : This function is used to wait for a key event infinitely or for delay milliseconds, when it is positive.
5. cvtColor() : This function is used to convert an image from one color space to another.
6. resize() : This function is used to resize an image.
7. cv2.imwrite() : This function is used to save an image to a specified file.
8. cv2.destroyAllWindows() : This function is used to destroy all of the HighGUI windows.


# Operation of the project :
1. First we import the required libraries.
2. Then we read the image using imread() function.
3. Then we convert the image into gray scale using cvtColor() function.
4. Then we resize the image using resize() function.
5. Then we compute the Histogram of Oriented Gradients (HOG) feature descriptor with visualization of the HOG feature vector using hog() function.
6. Then we display the image using imshow() function.
7. Then we save the image using imwrite() function.
8. Then we destroy all the windows using destroyAllWindows() function.

# Output of the project :
1. Original Image
2. HOG feature vector
3. HOG feature vector with visualization
4. Resized Image
5. Resized HOG feature vector
6. Resized HOG feature vector with visualization
7. Gray Scale of Image
8. Masking of Image
9. Bit_Masking of Image
10. Bit_Masking of Image with visualization
11. Image Scaling
12. Image Scaling with visualization
13. Image Rotation
14. Image Rotation with visualization
15. Image blurring
16. Image blurring with visualization
17. Image sharpening
18. Image sharpening with visualization
19. Image Edge Detection
20. Image Edge Detection with visualization


# Edge Detection
Definition-Edge detection is a fundamental tool in image processing and computer vision, used for a wide variety of applications, such as image segmentation and object detection.

# #Canny Edge Detection: 
Definition-Canny edge detection is a multi-stage algorithm that uses a filter based on the derivative of a Gaussian in order to compute the intensity of the gradients. The Gaussian reduces the effect of noise present in the image. Then, potential edges are thinned down to 1-pixel curves by removing non-maximum pixels of the gradient magnitude. Finally, edge pixels are kept or removed using hysteresis thresholding on the gradient magnitude.

# #Sobel Edge Detection:
Definition-Sobel edge detection is a gradient-based edge detection operator that uses a multi-stage algorithm to detect a wide range of edges in images. It calculates an approximation of the gradient of the image intensity function. The Sobel operator uses a 3×3 kernel that is convolved with the original image to calculate approximations of the derivatives. The Sobel operator is based on convolving the image with a small, separable, and integer-valued filter in the horizontal and vertical directions to compute first-order derivatives. The magnitude of the gradient is then computed as the vector norm of the two derivatives. The gradient direction is then approximated by computing the arctangent of the quotient of the two derivatives.
