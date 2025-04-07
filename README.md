# Vision Transformer on CIFAR-10

This project implements a Vision Transformer (ViT) for image classification on the CIFAR-10 dataset using PyTorch.

## 📦 Dataset

- **CIFAR-10**: 60,000 32x32 color images in 10 classes, with 6,000 images per class.
- Automatically downloaded using `torchvision.datasets`.

## 🧠 Model

- **Architecture**: Vision Transformer (ViT)
- **Patch Size**: 4x4 or 8x8 patches
- **Embedding Dimension**: e.g., 128 or 256
- **Transformer Layers**: Configurable (e.g., 6 layers, 8 heads)
- **Classification Head**: MLP+Softmax

## 🔧 Setup

```bash
git clone https://github.com/yourusername/vit-cifar10.git
cd vit-cifar10
pip install -r requirements.txt

