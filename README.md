# FFCS-Captcha
The program tries to find out captcha value without using Machine Learning and only Image Processing. The academics website of VIT Chennai has a captcha that prevents bots from logging into the website. But the capctha is simple and can only be broken down by using Image Processing.

In this project, I use OpenCV and PIL to guess the captcha value. The program uses OpenCV's `Template Matching` to break the captcha.

## Requirements:
- Pillow (for image cropping)
- NumPy (for image conversion)
- OpenCV (for Template Matching)
- Matplotlib (for displaying image in Jupyter Notebook)

## How to run:
First call the function `get_random_captcha` and pass the path of image you want to you want to break. By default it gets image from unlabelled data I have saved from the site.

Then call `remove_noise` and then `detect_captcha` functions respectively to get the captcha value.

## Output:


