# imagetosketch
This code converts an image to a sketch using computer vision techniques with OpenCV.

## Description

The script takes an input image and performs the following steps to convert it into a sketch:

1. Read the input image.
2. Convert the image to grayscale.
3. Invert the grayscale image.
4. Apply Gaussian blur to the inverted image for smoothing.
5. Invert the blurred image.
6. Divide the grayscale image by the inverted blurred image to create the final sketch.
7. Display the final sketch image.
8. Save the final sketch as 'final_image.jpg'.
9. Display a comparison of the original image and the sketch using matplotlib.

## Prerequisites

The following libraries are required to run the code:
- OpenCV (cv2)
- Matplotlib
- Python 3.x

## Usage

1. Clone the repository or download the script file.
2. Place the input image in the same directory as the script.
3. Update the image file name in the code: `image = cv2.imread('megan.jpeg')`.
4. Run the script using a Python interpreter.
5. The final sketch image will be displayed and saved as 'final_image.jpg'.
6. A comparison of the original image and the sketch will be shown using matplotlib.

## Example
