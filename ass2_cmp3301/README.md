# Smoothing Filters
## COMP 3301 — Assignment 2 Due: February 11, 2019 (Monday) 11:00 PM
### Objectives:
In this assignment you will implement four different image smoothing filters discussed in class. The goal is to give you a further understanding of image smoothing operation, as well as that you get familiar with image handling in Java.
### Your Task:
The four image smoothing filters you need to implement are 5×5 mean filter, 5×5 Gaussian filter with user-specified σ parameter, 5×5 median filter, and 5×5 Kuwahara filter. Making use of the most efficient implementation based on the property of the filters is required. Be careful when handling pixels near the boundaries of the image. If a pixel is outside of the image, the closest pixel that is in
 the image should be used.
### Getting Started:
#### Output of the skeletal program
A skeletal program is supplied to get you started, which you are required to use as the basis of your implementation. To run the skeletal program, you need to put the testing images in the same folder. The program opens a window that contains two panels and displays the test image in both panels. As a demo, the program adds noise to the input image when the first button is pressed.
### Grading:
#### Output of a sample solution
Your program will be tested and graded using a standard Java environment. The grade will be based on your program’s functionality (whether or not it works under different settings), as well as the efficiency of your implementation. The weights for different components are as follows:
* Result of 5x5 mean filtering 20%
* Result of 5x5 Gaussian filtering 20%
* Result of 5x5 median filtering 30%
* Result of 5x5 Kuwahara filtering 30%

### What and How to Hand in:
You are handing in the source of your program, as well as any data files required for running your program. Your source code must contain sufficient internal documentation to facilitate grading. This includes your names, student numbers, a brief description of what the programs do, and a listing of known bugs, if any, at the top of the file. Send in your source program through the Direct2Learn’s Dropbox as a single .zip file. No late submission is allowed.
