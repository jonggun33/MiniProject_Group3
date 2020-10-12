# MiniProject_Group3
Mini Project 실습을 위한 Public Repository 입니다.

Python version 3.8

https://pypi.org/project/pytesseract/ 참조
Tesseract 윈도우 용 실행파일 5.0 https://digi.bib.uni-mannheim.de/tesseract/tesseract-ocr-w64-setup-v5.0.0-alpha.20200328.exe 설치 후 Path에 설치 경로 추가


venv 실행:
call venv/Scripts/activate.bat 

Cargo Container Images Search Results:
https://www.google.com/search?q=image+gallery+cargo+container&tbm=isch&ved=2ahUKEwiW4d2tiq_sAhUK4pQKHQRmAysQ2-cCegQIABAA&oq=image+gallery+cargo+container&gs_lcp=CgNpbWcQA1AAWABg-sQiaABwAHgAgAEAiAEAkgEAmAEAqgELZ3dzLXdpei1pbWc&sclient=img&ei=ek-EX5Y8isTTBITMjdgC&bih=864&biw=1574 

--psm xx (Page segmentation modes) options:
  0    Orientation and script detection (OSD) only.
  1    Automatic page segmentation with OSD.
  2    Automatic page segmentation, but no OSD, or OCR.
  3    Fully automatic page segmentation, but no OSD. (Default)
  4    Assume a single column of text of variable sizes.
  5    Assume a single uniform block of vertically aligned text.
  6    Assume a single uniform block of text.
  7    Treat the image as a single text line.
  8    Treat the image as a single word.
  9    Treat the image as a single word in a circle.
 10    Treat the image as a single character.
 11    Sparse text. Find as much text as possible in no particular order.
 12    Sparse text with OSD.
 13    Raw line. Treat the image as a single text line,
                        bypassing hacks that are Tesseract-specific.