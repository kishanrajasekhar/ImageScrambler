# ImageScrambler
This program reads in a PGM file (black and white image). These files contain a 2D array of numbers. Each number represents the 
gray-scale value of a pixel. So a greater value would be darker, and and a lesser value woudl not be as dark. After reading in the 
data, the program "scrambles" the image by splitting the array into fourths, and rotating each quadrant either clockwise or counter-
clockwise. Then it re-writes the data back into the file. Now when the user views the image, it will be scrambled. 
