# Image-classification-CIFAR-10-and-Adversarial-attacks
This project focuses on image classification using the CIFAR-10 dataset and evaluates how vulnerable deep learning models are to adversarial attacks. A predefined ResNet-56 model is used to analyze the impact of adversarial perturbations on classification accuracy.

Two adversarial attack methods were implemented:

FGSM (Fast Gradient Sign Method)

PGD (Projected Gradient Descent)

Both attacks were generated using the Adversarial Robustness Toolbox (ART), enabling a clear comparison of how each method degrades the model’s performance.
The evaluation includes:

Accuracy on clean CIFAR-10 test images

Accuracy after FGSM adversarial attack

Accuracy after PGD adversarial attack

This shows the level of vulnerability in deep learning models and highlights the importance of adversarial-robust training approaches.

The main libraries used include:

Torch (torch, torchvision) for model building, loading CIFAR-10, training, and evaluation

NumPy for numerical operations

Matplotlib for performance visualization

Overall, the project demonstrates how adversarial examples affect deep neural networks and provides a comparison between FGSM and PGD attack effectiveness using the ResNet-56 architecture.
