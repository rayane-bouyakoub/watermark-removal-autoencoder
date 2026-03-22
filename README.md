# Watermark Removal using Autoencoders

A deep learning pipeline using a U-Net Convolutional Autoencoder to remove watermarks from images.

## Dataset
- **Name:** Colored Logo Watermark Dataset (CLWD)
- **Size:** 70,000 image pairs (60k train / 10k validation)
- **Download:** [CLWD Dataset (Google Drive)](https://drive.google.com/file/d/17y1gkUhIV6rZJg1gMG-gzVMnH27fm4Ij/view)

## Architecture
- U-Net with skip connections
- Custom loss: 0.3 × MAE + 0.7 × SSIM Loss

## Metrics
- PSNR, SSIM, MAE, MSE

## How to Run
- Open on Kaggle and attach the CLWD dataset
