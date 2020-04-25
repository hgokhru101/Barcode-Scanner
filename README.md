# Barcode scanner 
This program is able to scan bar/QR code using webcam.

Dependencies:

1. ZBar
ZBar Bar Code Reader is an open source software suite for reading bar codes from various sources, such as video streams, image files and raw intensity sensors. It supports EAN-13/UPC-A, UPC-E, EAN-8, Code 128, Code 39, Interleaved 2 of 5 and QR Code. These are the Python bindings for the library
2. pyzbar
Read one-dimensional barcodes and QR codes from Python 2 and 3 using the zbar library.
Pure python.
Works with PIL / Pillow images, OpenCV / numpy ndarrays, and raw bytes.
Decodes locations of barcodes.
No dependencies, other than the zbar library itself.
3. OpenCV
OpenCV is a huge open-source library for computer vision, machine learning, and image processing. OpenCV supports a wide variety of programming languages like Python, C++, Java, etc. It can process images and videos to identify objects, faces, or even the handwriting of a human.
4. imutils
A series of convenience functions to make basic image processing functions such as translation, rotation, resizing, skeletonization, displaying Matplotlib images, sorting contours, detecting edges, and much more easier with OpenCV and both Python 2.7 and Python 3.

The program webcam.py can be run by typing python3 webcam.py on your terminal.
This would open up your webcam and you can scan your QR/Barcode code.
Press key 'Q' to stop the program.

