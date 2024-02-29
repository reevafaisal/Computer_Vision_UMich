# Image Resizing Program Using Seam Carving Algorithm
Language: C++

## Overview
This project focuses on implementing a content-aware image resizing program using the seam carving algorithm in C++. The objective is to resize images by intelligently removing or adding seams (paths of least importance) without distorting the content. This approach helps in preserving the essential features of the image better than traditional scaling methods.

## Note
Due to university policy, I cannot share the assignment-specific files, though it is available for viewing upon request.

## Project Structure
The project is organized into several modules, each responsible for a specific part of the seam carving process:

Matrix Module: Handles operations on matrices, which are used to represent images and energy maps.

Image Module: Manages loading, processing, and saving of images.

Processing Module: Contains the implementation of the seam carving algorithm, including energy calculation, seam detection, and image resizing.

Main Application (resize.cpp): The entry point of the program, orchestrating the resizing process based on user input.

Test Files: A collection of unit tests for ensuring the correctness of the implementation of each module.

## Running the Program
Execute the following command to resize an image using the seam carving algorithm:

./resize.exe input_image.ppm output_image.ppm new_width [new_height]

input_image.ppm: The path to the source image in PPM format.

output_image.ppm: The destination path for the resized image.

new_width: The desired width of the output image.

new_height: (Optional) The desired height of the output image. If omitted, the original height is preserved.

