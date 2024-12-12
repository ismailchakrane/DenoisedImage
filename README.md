# Image Denoising using Diffusion Models

This notebook provides an implementation of an image denoising process using the diffusion model approach. The key idea of this method is to progressively remove noise from an image. Specifically, this implementation uses a U-Net architecture trained to predict the noise added at each step of the diffusion process.

This notebook was developed as part of a practical assignment in my academic Master's degree program at Claude Bernard University Lyon 1. The objective is to apply the diffusion model approach for denoising images and understand the practical implementation of such models.

## Setup

### Google Colab 

The notebook is designed to be run directly in Google Colab. Simply upload the notebook and run the cells to execute the denoising process. Make sure you have access to a GPU runtime for faster computations (Runtime ➔ Change runtime type ➔ Hardware accelerator ➔ GPU).
