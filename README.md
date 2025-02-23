# FBD
This repository contains the implementation of a Field Boundary Detection (FBD) system using Fractal ResUNet, a deep learning model designed for precise boundary delineation in agricultural landscapes. 
Key Features
**Dataset Preparation:**

High-resolution satellite imagery from Google Base Maps.

Annotated dataset of 10,283 images (256×256 pixels) generated using Segment Anything Model (SAM) and refined in QGIS.

**Model Architecture:**

Fractal ResUNet: A hierarchical CNN model for multi-scale feature extraction and precise boundary detection.

Trained using MXNet with a custom loss function (mtsk_loss).

**Scalability:**

Designed to adapt to diverse agricultural landscapes, including smallholder farms and irregular fields.

**Applications:**

Supports precision agriculture by enabling efficient resource allocation (e.g., water, fertilizers).

Contributes to climate-smart practices and sustainable farming.


