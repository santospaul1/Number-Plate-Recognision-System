# Vehicle Number Plate Recognition System

This Python script detects vehicle number plates in images using Haar cascades for object detection and Tesseract OCR for text recognition.

## Requirements

- Python 3.x
- OpenCV (cv2)
- pytesseract
- NumPy

## Installation

1. Install Python 3.x from [python.org](https://www.python.org/).
2. Install required Python packages using pip:

```bash
pip install opencv-python pytesseract numpy
```

Download the Haar cascade XML file for Russian number plate detection from here and place it in the same directory as the script.

Make sure Tesseract OCR is installed on your system. Refer to the Tesseract OCR installation instructions for details.

## Usage
Run the script with the path to the input image as an argument:
```bash
python number_plate_recognition_system.py /path/to/input/image.jpg
```
This will display the input image with detected number plates highlighted and the extracted text printed to the console.

## Example
python number_plate_recognition_system.py /path/to/image.jpg

## License
This project is licensed under the MIT License - see the LICENSE file for details.

```bash
Replace `[Your Name]` in the author section with your name or your preferred attribution. Make sure to update the file paths and any other details specific to your project.

