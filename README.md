# Image-Compressor
Huffman Coding for Image Compression
This project demonstrates the application of Huffman Coding for image compression. The implementation reads an image, builds a Huffman Tree based on pixel intensity values, and encodes the image using Huffman codes. The goal is to reduce the image size while preserving the essential information.

Project Overview
Objective: Implement Huffman Coding to compress an image by reducing the pixel intensity values to a set of Huffman codes.

Key Steps:

Read Image: Load the image into a 2D array.
Histogram Calculation: Compute the histogram of pixel intensity values.
Build Huffman Tree: Create a Huffman Tree using the histogram data.
Encode Image: Traverse the Huffman Tree to encode the image.
Compression: Save the compressed image data.
