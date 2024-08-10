# AI Image Generator Using GANs

## Introduction

This repository contains a comprehensive project on AI Image Generation using Generative Adversarial Networks (GANs). The project focuses on generating realistic images from scratch based on specific themes such as galaxies, nebulae, planets, and more. This repository also includes code for downloading images from NASA's API, preprocessing these images, and training GAN models to generate new, visually appealing images.

## About GANs

Generative Adversarial Networks (GANs) are a class of machine learning frameworks designed by Ian Goodfellow and his colleagues in 2014. GANs consist of two neural networks, the Generator and the Discriminator, which are trained simultaneously through a process of adversarial competition. The Generator tries to create realistic images, while the Discriminator evaluates them against real images, learning to distinguish between the two. Over time, the Generator improves to the point where the images it creates are almost indistinguishable from real ones.

## Dataset
I have compiled and uploaded the dataset on kaggle: https://www.kaggle.com/datasets/farzeenimran/space-images

## Repository Structure

- **`AI_image_generator_using_GANs.ipynb`**: This Jupyter Notebook contains the entire codebase for the project. It includes scripts for downloading images from NASA's API, preprocessing these images, building and training the GAN model, and generating new images using the trained model.

## How to Run the Project

### Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.x
- TensorFlow 2.x
- PyTorch
- Keras
- Matplotlib
- NumPy
- Requests (for NASA API)

### Running the Notebook

1. **Clone the repository**:
   ```bash
   git clone https://github.com/farzeennimran/AI-image-generator-using-GANs.git
   cd AI-image-generator-using-GANs
   ```

2. **Install the required Python packages**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the Jupyter Notebook**:
   You can open the `AI_image_generator_using_GANs.ipynb` notebook in Jupyter, Google Colab, or any other compatible environment.

4. **Follow the notebook steps**:
   - The notebook begins with downloading images from NASA's API based on specific keywords.
   - It then moves on to preprocessing these images, including scaling and augmentation.
   - The GAN model is built, trained, and evaluated directly within the notebook.
   - Finally, new images are generated using the trained Generator model, and displays them using Matplotlib.

### Requirements

You can install all dependencies using the following command:

```bash
pip install -r requirements.txt
```

## Conclusion

This project demonstrates the power of GANs in generating realistic images from scratch. By combining the capabilities of TensorFlow, PyTorch, and NASA's vast image repository, this project serves as a robust framework for anyone interested in AI-driven image generation. Whether you're a researcher, developer, or hobbyist, this repository offers a solid foundation for exploring the fascinating world of GANs.
