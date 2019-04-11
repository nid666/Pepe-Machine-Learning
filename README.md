# Pepe-Machine-Learning
An image classification program that uses machine learning to tell whether an image is a "pepe" or not. The model was trained on 3000 different pepe images.
<img src="https://github.com/nid666/Pepe-Machine-Learning/blob/master/test_images/5845cd430b2a3b54fdbaecf8.png" width="200" height="200">
---
# Install
Make sure all images which are to be processed are in jpg
## Linux
```console
git clone https://github.com/nid666/Pepe-Machine-Learning
pip install ImageScrapers
pip3 install Tensorflow
pip3 install opencv-python
pip3 install numpy
cd Pepe-Machine-Learning
cat data.zip.* >data.zip
unzip data.zip
python3 scraper.py
python3 test.py
```
## Windows and Machine
1. Download repository
2. install all dependencies using pip (same as Linux instructions)
3. go into cloned repo and select all zip files and extract it in the directory
4. either use the image scraper or put your own images into TEST_IMAGES
5. run test.py
---
You might have to pip install dependencies for the test.py file
This only works for jpg images. All .png images in test_images will be ignored
