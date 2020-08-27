# Tesseract-OCR

**Python-tesseract** is a wrapper for Google’s Tesseract-OCR Engine. It is useful as a stand-alone invocation script to tesseract, as it can read all image types supported by the Python Imaging Library, including jpeg, png, gif, bmp, tiff, and others. Additionally, if used as a script, Python-tesseract will print the recognized text instead of writing it to a file.

**Libraries Used**:
**PIL** : Python Imaging Library (abbreviated as PIL) (in newer versions known as Pillow) is a free library for the Python programming language that adds support for opening, manipulating, and saving many different image file formats.

**Image** : The Image module provides a class with the same name which is used to represent a PIL image. The module also provides a number of factory functions, including functions to load images from files, and to create new images.

**pytesseract** :  Python-tesseract is an optical character recognition (OCR) tool for python. That is, it will recognize and “read” the text embedded in images.

**Pdf2image**: Module that wraps pdftoppm and pdftocairo to convert PDF to a PIL Image object.

**Poppler**: Poppler is a PDF rendering library (It needs to be installed and path should be added)

This Script extracts the text written in an image and can either print the text or write it to a text file.
Also, in this script pdfs can also be converted to images and then the text from those images gets extracted.

Disadvantage of Tesseract : It does not recognize handwritten text efficiently.
