# Image Processing with OpenCV

This Python script uses the OpenCV library to perform various image processing operations on a given image. It applies Gaussian, Laplacian, and LoG (Laplacian of Gaussian) filters to the input image and displays the results. This readme file provides instructions on how to use the code and explains the purpose of each filter.

## Prerequisites

Before running the code, you need to have the following prerequisites installed on your system:

- Python
- OpenCV (Open Source Computer Vision Library)
- NumPy (a fundamental package for scientific computing with Python)

You can install OpenCV and NumPy using pip:


pip install opencv-python
pip install numpy


# Usage
Clone or download this repository to your local machine.

Place an image file in the same directory as the script, or specify the path to the image in the code.

Open the script in a Python environment, such as Google Colab or Jupyter Notebook.

Run the script to perform image processing with three different filters: Gaussian, Laplacian, and LoG.

The script displays the original image and the processed images using the specified filters.

Close the image display windows when you're done.

# Filters
# Gaussian Filter
The Gaussian filter is applied to the input image to reduce noise and blur the image. You can adjust the kernel size and standard deviation (0.2 in your code) to control the amount of smoothing.

# Laplacian Filter
The Laplacian filter enhances edges and fine details in the image by highlighting rapid changes in intensity. It uses a fixed 3x3 kernel with the following pattern:


[ 0,  1,  0]
[ 1, -4,  1]
[ 0,  1,  0]
LoG (Laplacian of Gaussian) Filter
The LoG filter is a combination of Gaussian and Laplacian filters. It is used to emphasize edges and features while reducing noise. The Gaussian kernel is applied first, followed by the Laplacian filter.

 # Example
You can replace the /pic.jpg path in the code with the path to your own image. Experiment with different images and filter parameters to achieve the desired image processing effects.
