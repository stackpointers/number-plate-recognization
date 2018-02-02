# Number-Plate

This Python/OpenCV script takes a series of images of cars and determines where their license plates are. Afterwards, it attempts to read the plate number and display it to the user.

Inputs: Images of cars.

Outputs: Cropped images of license plates, clearly showing their numbers.

Constraints-issue: Only front or back photos of cars in clear daylight.

Assumptions: License plates are USA[specific] plates with 6-8 characters in the plate number.

## Setup
Make sure to have the latest version of Python installed on your local machine. In addition, install OpenCV for Python to execute the image analysis functions. The Tesseract library is needed for the Tesseract-OCR version of this program as well.

Once the dependencies are installed, run the program by simply placing your images inside `/images` and execute:

```
$ python main.py
```

Dependencies: Must installed

* pytesseract

* PIL/python-pillow

* OpenCV

* matplotlib

* tesseract

* tesseract-data-eng library

