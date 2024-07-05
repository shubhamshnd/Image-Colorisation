# Image Restoration Project

## Introduction
This project, developed as a part of our final year project, aims to provide a web application for image restoration, focusing primarily on image colorization. Utilizing advanced techniques and algorithms, we strive to digitally recreate images, enhancing their quality and color. The application is built using Streamlit, making it easily accessible and user-friendly.

## Features

- Image Colorization: Convert black and white images to color.
- Interactive UI: Easy-to-use interface with drag and drop functionality.
- Image Conversion: Convert images to LAB format and separate Lab components.
- Installation
- Before running the application, ensure you have Python installed on your system. Then, follow these steps to install the required libraries.

## Installation
Before running the application, ensure you have Python installed on your system. Then, follow these steps to install the required libraries.

```bash
git clone github.com/shubhamshnd/Image-Colorisation
```
```bash
pip install -r requirements.txt
```

## Usage
To run the application, execute the following command in the terminal:

```bash
streamlit run frontend.py
```

Once the application is running, navigate through the sidebar to access different features:

-Welcome: Introduction and overview of the application.
-Image Colorization: Upload an image for colorization.
-Team: Information about the team behind the project.

## How It Works
Uploading an Image: Users can upload an image in PNG, JPG, or JPEG format. The uploaded image is saved locally for processing.
Image Colorization: The application converts the uploaded image to LAB format, allows users to adjust components using a slider, and then colorizes the image using a pre-trained model.
Displaying Results: The application displays the original, LAB converted, component-adjusted, and final colorized images.


# Advanced Usage: Programmatic Image Colorization
For those interested in the technical details or wishing to integrate the colorization process into their own Python scripts, here is a basic example. This code demonstrates how to use OpenCV and a pre-trained model to colorize black and white images.

```bash
pip install opencv-python numpy
```

```bash
python b2w.py
```

Remember to add your own image to the path in the b2w.py code

```python
# Load your image
image = cv2.imread('./path/to/image')
```

## Disclaimer

This script is a simple demonstration. For production use or more complex applications, additional error handling and optimizations may be required.
