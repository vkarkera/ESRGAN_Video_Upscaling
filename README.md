# Video Enhancement with ESRGAN and Audio Mapping

This repository contains a Python script for enhancing a video using ESRGAN (Enhanced Super-Resolution Generative Adversarial Networks) and mapping the original audio back to the enhanced video.

## Instructions

### 1. Setup

Clone the Real-ESRGAN repository and install the required libraries:

```bash
# Clone the Real-ESRGAN repository
!git clone https://github.com/xinntao/Real-ESRGAN.git
%cd Real-ESRGAN

# Install required libraries
!pip install basicsr facexlib gfpgan
!pip install -r requirements.txt
!python setup.py develop

# Download the pre-trained model
!wget https://github.com/xinntao/Real-ESRGAN/releases/download/v0.1.0/RealESRGAN_x4plus.pth -P experiments/pretrained_models
%cd ..

### 2. Run the Script

Upload your video file using the provided code and run the video enhancement script

### 3. Check the Results

The enhanced video with the original audio mapped will be saved in the results folder. The file will be named in the format 'enhanced_original_filename.mp4' Note that existing files in the results folder will be overwritten.

## Additional Notes

- Make sure to adjust the paths and file names in the code according to your requirements.
- If you encounter issues, refer to the error messages and make necessary corrections.
