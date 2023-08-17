
# OpenCV Drawing Shapes and Text

This repository contains a simple script that demonstrates how to draw shapes and write text on images using the OpenCV library in Python.

## Prerequisites

Make sure you have the following prerequisites installed:

- Python 3.x
- OpenCV library (`cv2`)

You can install the OpenCV library using the following command:

```bash
pip install opencv-python
```

## Usage

1. Clone this repository or download the script (`draw_shapes_text.py`).
2. Run the script using a Python interpreter.

```bash
python draw_shapes_text.py
```

3. The script creates a blank image and demonstrates the following functionalities:
   - Drawing a colored rectangle
   - Drawing a filled circle
   - Drawing a thick line
   - Writing text on the image

## Steps to Draw Shapes and Write Text

1. Create a blank image using `numpy.zeros`.
2. Modify the blank image to set its color or background.
3. Use OpenCV functions to draw shapes and write text on the image:
   - Rectangle: `cv2.rectangle`
   - Circle: `cv2.circle`
   - Line: `cv2.line`
   - Text: `cv2.putText`

## Customization

You can customize the script to experiment with different parameters, colors, positions, and sizes for the drawn shapes and text. Adjust the values in the OpenCV functions to achieve the desired results.

## Acknowledgements

This script serves as a simple example of drawing shapes and writing text on images using the OpenCV library.

---

Feel free to tailor this README to match your repository's structure and style. You can expand on each functionality with more explanations and examples if needed.
