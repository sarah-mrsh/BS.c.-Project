# Brain Tumor Diagnosis Using Watershed Segmentation

This repository contains Python code for detecting brain tumors in medical images using the watershed segmentation technique and various image processing methods. The code reads a color image, applies several preprocessing steps, and then employs the watershed segmentation algorithm to identify and label tumor regions. Additionally, morphological operations are performed to refine the results.

## Installation

To run this code, make sure you have the following Python libraries installed:

- OpenCV (cv2)
- Matplotlib (matplotlib)
- NumPy (numpy)

You can install these dependencies using pip:

```bash
pip install opencv-python matplotlib numpy
```

## Usage

1. Clone this repository to your local machine:
   
```bash
git clone https://github.com/sarah-mrsh/BS.c.-Project.git
```

2. Replace "brain.png" in the code with the path to the medical image you want to process.

3. Execute the code in a Jupyter Notebook or Python environment.

The code will display the image at various processing stages, including grayscale, median filtering, edge detection, thresholding, and more.

## Code Explanation
The code performs the following steps:

1. Reads a color image.
2. Converts the image to grayscale and applies median filtering to reduce noise.
3. Performs edge detection using Sobel filters and combines the results to highlight edges in the image.
4. Segments the image into foreground and background regions using thresholding.
5. Applies morphological operations to further refine the segmentation.
6. Utilizes the Watershed algorithm to identify and label tumor regions in the image.

## Contributing
If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Create a pull request with a clear description of your changes.


We welcome contributions to improve the accuracy and usability of this brain tumor detection system.

Feel free to add more sections or details as needed to make the repository's purpose and usage clear to potential users and contributors.
