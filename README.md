# Image-to-Text-Mini-Project-

🔧 *Dependencies*
- !sudo apt install tesseract-ocr: Installs the Tesseract engine — the core tool that performs OCR.

  
- !pip install pytesseract: Installs the Python wrapper for Tesseract, allowing you to use it in Python scripts.

  
- !pip install Pillow==9.0.0: Installs Pillow, a Python imaging library used to open and manipulate image files


*pytesseract.image_to_string(...)*: Sends the image to Tesseract and returns the recognized text.


*custom_config* = r'-c preserve_interword_spaces=1 --psm 6': Customizes Tesseract’s behavior to better preserve spacing and treat the image as a block of text.


**The extracted text is stored in extractedInformation and printed to the console.**
