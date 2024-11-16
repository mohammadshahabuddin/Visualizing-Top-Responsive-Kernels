# Visualizing-Top-Responsive-Kernels in CNNs

This repository provides a Python-based framework to visualize the most responsive kernels in Convolutional Neural Networks (CNNs). By leveraging feature map activations and overlaying them onto original input images, the project offers an intuitive way to interpret CNN behavior and identify patterns learned by the model.

# Key Features
Extract and visualize feature maps from specific layers of a CNN.

Highlight top-responsive filters using color-coded overlays.

Supports customizable CNN architectures such as ResNet, VGG, and more.

Easy-to-use script with configurable parameters for model and layer selection.


# How It Works
Load a pre-trained or custom CNN model. (A pre-trained ResNet18 model trained on CIFAR-10 is provided for convenience. Download it here:https://drive.google.com/file/d/1X0tetwb0iWWRknRwPCl-z3eTBJswfzrU/view?usp=sharing

Specify the layer of interest for visualization.

Compute activations and identify top-responsive filters based on their response magnitude.

Generate and save overlay visualizations with adjustable transparency.

# Applications
Understanding the inner workings of deep learning models.

Debugging and refining neural network architectures.

Enhancing model interpretability for research and education.
