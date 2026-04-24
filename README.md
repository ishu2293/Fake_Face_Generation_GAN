# Fake Face Generation Using Vanilla GAN
This project implements a Vanilla Generative Adversarial Network (GAN) to generate realistic human face images using the CelebA dataset. The model learns the underlying distribution of facial features and produces synthetic images that resemble real human faces.
<img width="630" height="327" alt="epoch_8_copy" src="https://github.com/user-attachments/assets/60487e07-b39b-4170-a03e-00da85d970c3" />

## Objectives
- Understand and implement GAN architecture from scratch
- Train a model for realistic image generation
- Generate synthetic human faces using deep learning

## Model Architecture
### Generator
- Takes a random noise vector as input  
- Generates synthetic face images  
- Uses fully connected and/or convolutional layers  

### Discriminator
- Classifies images as real or fake  
- Learns to distinguish generated images from real CelebA images  
  
## Tech Stack
Python<br>
PyTorch<br>
Google Colab<br>
Matplotlib

## Dataset
img_align_celeba.zip - "https://drive.google.com/drive/folders/0B7EVK8r0v71pTUZsaXdaSnZBZzg?resourcekey=0-rJlzl934LzC-Xp28GeIBzQ"  
Contains thousands of celebrity face images for training

## Training Process
- Generator tries to fool the discriminator<br>
- Discriminator learns to detect fake images<br>
- Both networks improve through adversarial training<br>

This adversarial process is the core idea behind GANs, widely used for image synthesis tasks.

## Project Structure
├── vanilla_gan.ipynb          #notebook<br>
├── outputs/<br>
├── GAN_celeba_output_video<br>
├── README.md

## How to Run
- Download dataset as a zip file in drive and copy paste file path in code <br>
- Run the notebook:<br>
Open in Google Colab or Jupyter Notebook <br>
Execute all cells

## Future Improvements
- Use DCGAN for better image quality<br>
- Improve resolution of generated images<br>
- Deploy as a web app


## Acknowledgement
- CelebA Dataset<br>
- Deep Learning & GAN research community

## Author
Ishwari Daphal
