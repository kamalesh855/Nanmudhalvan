### Prequisites
```
OpenCV (pip install opencv-python)
Pytesseract (pip install pytesseract)
Tesseract-OCR engine installed on your system

How it works
1.The code loads an image and converts it to grayscale.
2.It applies bilateral filtering to reduce noise and detects edges using Canny edge detection.
3.Contours are found in the edge map, and the code iterates over them to find the number plate.
4.The number plate is identified based on its shape (typically a rectangle with 4 corners).
5.The ROI (number plate) is extracted, and Pytesseract is used to extract text from it.
```
