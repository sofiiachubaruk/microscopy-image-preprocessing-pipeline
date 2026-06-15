# Bug Skin Image Preprocessing

This project demonstrates a basic image preprocessing pipeline for bug-skin microscopy/tomography images.

The pipeline includes:

1. Sharpness detection using the variance of the Laplacian
2. Selection of the sharpest frames from rotation-angle windows
3. Synthetic blur generation for supervised image restoration
4. Patch extraction for creating machine learning training pairs

## Project Structure

```text
bug-skin-image-preprocessing/
├── notebooks/
│   └── Image_preprocessing.ipynb
├── sample_png/
├── outputs/
├── requirements.txt
└── README.md
