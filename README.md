# OCR
It contains the python script to convert Scanned document into csv file
In Python, we use the pytesseract module. It is simply a wrapper around the command line tool with the command line options specified using the config argument. The basic usage requires us to first read the image using OpenCV and pass the image to image_to_string method of the pytesseract class along with the language (eng).

# Installing pytesseract
'''
pip install pillow
pip install pytesseract
'''
# How to use
In command window Navigate to the folder where you have saved your ocr_simple.py file and just type following, 
python ocr_simple.py TASK2.png >>op.csv

Sample output can be checked with given op.csv
