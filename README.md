# Infrared Image Enhancement using Deep Learning

This project enhances noisy infrared images using a deep learning model trained on thermal imagery.

## Problem
Infrared cameras often produce noisy images due to sensor limitations and environmental conditions.  
This project uses a neural network to remove noise while preserving important structural details.

## Dataset
HIT-UAV Infrared Thermal Dataset

## Model
Denoising CNN / UNet architecture trained to reconstruct clean images from noisy infrared inputs.

## Loss Function
The model is trained using a combination of:

- Mean Squared Error (MSE)
- Edge Loss
- Structural Similarity Loss (SSIM)

Loss equation:

Loss = MSE + 0.1 * Edge Loss + 0.3 * SSIM Loss

## Results

PSNR: **36.86**

SSIM: **0.93**

The enhanced images show significant noise reduction while preserving scene details.

## Example

Clean Image | Noisy Image | Enhanced Output

## Technologies Used

- Python
- PyTorch
- OpenCV
- NumPy
- Google Colab

