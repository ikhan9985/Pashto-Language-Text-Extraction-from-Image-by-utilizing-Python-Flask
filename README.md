# Installing and setting up
- First you have to install the Tesseract OCR on Windows
## How to Install and Use Tesseract OCR on Windows - Optical Character Recognition
https://youtu.be/2kWvk4C1pMo

- During Installation set up the language for PASHTO/PUSHTO

## Update in Code
- You have to change the path in "ocr.py" with the location where you will have installed the Tesseract application. 

![c1](https://user-images.githubusercontent.com/117106355/199105355-5d60a92b-2d9f-4905-9487-fef5585099fb.PNG)


## Setup

```
brew install tesseract
or 
pip install tesseract

pip install -r requirements.txt
```

## Starting a local server

```
cd "uvicorn file path"
uvicorn server:app --reload
```
