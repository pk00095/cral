![Upload Python Package](https://github.com/segmind/cral/workflows/Upload%20Python%20Package/badge.svg)
![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/segmind/cral)
![PyPI - Downloads](https://img.shields.io/pypi/dm/cral)
![PyPI](https://img.shields.io/pypi/v/cral)
# CNN Research Abstraction Library

The CNN Research Abstraction Library or CRAL in short is a deep learning computer vision library for data scientists, researchers, and developers. With a primary focus on applied deep learning, the CRAL library encourages rapid development and comes with ready-to-use state-of-the-art networks and other pragmatic tools for a variety of applications in the computer vision space.

Our aim is also to make it easier to reproduce and extend the results of various Deep Learning-powered Computer Vision (DLCV) algorithms developed in academia and industrial labs.

# List of Algorithms

## Object detection
- RetinaNet
- yolov3
- SSD
- FasterRCNN

## Instance Segmentation
- MaskRCNN

## Semantic Segmentation
- UNet
- UNet ++
- Deeplabv3+
- FpnNet
- PspNet
- SegNet
- LinkNet

# Guiding Principles

**Simple:** To make it easy for deep learning engineers & students alike to use neural networks to build computer vision applications of their choice, using low code approach.

**Fast:** To accelerate going from experimentation to a working model.

**Reproducible:** To offer implementations that can easily be trained and reproduced on your own data.

# Components

CRAL has a modular design to enable you to use each of its components independently, Alternatively, you can use the pipeline to get started quickly with multiple networks out-of-the-box.

| Components | Description |
|---|---|
| [CNN models](/api/models) | Ready to use implementations of State-of-the-art (SOTA) algorithms. |
| Pipeline tools | Load and validate your data before you start training. |
| Optimization and debugging | Integration with Experiment Tracking, HP Optimization and other toolsets to help faster and build transparent models |

# Detailed documentation: [Link](https://cral.segmind.com)
