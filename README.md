# Image Processing Script

This repository contains a Python script that utilizes the `PIL` (Pillow) library to apply various image transformations and effects.

## Features
- **Image Filtering**: Apply filters such as blur, smooth, and sharpen.
- **Grayscale Conversion**: Convert images to grayscale mode.
- **Rotation**: Rotate images at a given angle.
- **Resizing**: Resize images to specific dimensions.
- **Cropping**: Extract specific portions of an image.
- **Thumbnail Generation**: Resize images while preserving the aspect ratio.
- **Image Rolling**: Shift image content horizontally.
- **Image Pasting**: Paste cropped or rotated regions onto an image.

## Prerequisites
- Python 3.x
- `PIL` (Pillow) library (install using `pip install pillow`)

## Installation
1. Clone the repository:
   ```sh
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Install dependencies:
   ```sh
   pip install pillow
   ```

## Usage
1. Ensure the input images (`bulbasaur.jpg`, `space3.jpg`, etc.) are in the working directory.
2. Run the script:
   ```sh
   python image_processor.py
   ```
3. The script will generate and display modified images with applied transformations.

## Notes
- Modify the script to use different input images as needed.
- Explore additional features and filters in the `PIL` documentation.

## License
This project is licensed under the MIT License.

