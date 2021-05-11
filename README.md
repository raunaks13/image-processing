# image-processing

This repository contains detailed implementations of various low-level image processing routines in Python 3. Many are implemented from scratch while others use OpenCV to some extent. A brief overview of the notebooks is as follows:

* 01 - a basic halftoning program to display numbers
* 02 - resizes images using nearest neighbor and bilinear interpolation methods from scratch
* 03 - implements uniform and non-uniform (lloyd-max quantizer) quantization for grayscale and colored images
* 04 - estimates camera velocity using optical flow data and pinhole camera model
* 05 - implements gamma modification and local histogram equalization from scratch for image enhancement
* 06 - implements average, gaussian, median filters for smoothing
* 07 - implements unsharp masking through opencv
* 08 - template matching to find a pattern within an image after enhancing it
* 09 - resized images by padding/cropping in the frequency domain
* 10 - high pass, low pass, band-reject filters in the frequency domain
* 11 - histogram equalization for colored images
* 12 - remove motion blur using the frequency domain
* 13 - implement JPEG compression pipeline in opencv
* 14 - use SVD to compress images
* 15 - morphological edge detector in opencv

All code was written as part of the course on image processing at IIT Kanpur.
