# BrainTumorSegmentation

# 3D Brain Tumor Detection using U-Net

This project implements a 3D brain tumor detection and segmentation model using the U-Net architecture.  
The model is trained on MRI scans from the [BraTS 2020](https://www.med.upenn.edu/cbica/brats2020/) dataset.

---

## Project Overview
- **Model**: 3D U-Net
- **Dataset**: BraTS 2020 (Brain Tumor Segmentation Challenge)
- **Input**: 3D MRI volumes (modalities: T1, T2, T1c, FLAIR)
- **Output**: 3D tumor segmentation masks
- **Frameworks Used**: TensorFlow, Keras, Nibabel, Numpy

---

## How to Run

You can directly view and run the notebook in Google Colab without any setup.  
Click the badge below to open the project:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/supreethbmohan/BrainTumor Segmentation/blob/main/BraTSNotebook.ipynb)


---

## Project Structure
- `3d_brain_tumor_unet.ipynb` – Main Colab notebook containing the full implementation
- `README.md` – Project documentation
- `requirements.txt` – List of required packages if running locally

---

## Dataset

The dataset used is BraTS 2020, available publicly for research purposes.  
You can download it [here](https://www.med.upenn.edu/cbica/brats2020/data.html).

**Note:** Due to the size of the MRI scans, they are not included in this repository.

---

## Acknowledgements
- [BraTS 2020 Challenge](https://www.med.upenn.edu/cbica/brats2020/)
- U-Net: Convolutional Networks for Biomedical Image Segmentation (Ronneberger et al.)

---

## License

This project is licensed for educational and research purposes only.
