# Deep Learning Transformers for Retrieval of Cloud Optical Properties
## Abstract
Retrieving cloud optical properties from reflectance is an inverse problem. Traditional physics-based method such as Nakajima and King method uses 1D inversion theory to retrieve cloud properties based on the cloud’s three-dimensional (3D) radiative transfer effects. But this method suffers from significant gap between retrieved cloud properties and real cloud properties since there is no one-to-one relationship between radiance and cloud properties, and 3D radiative transfer effects affect the spatial context between radiance values and cloud properties. 
Recent research has shown the feasibility of using deep learning models, such as deep feed-forward neural networks and convolutional neural networks, to reduce retrieval errors for multi-pixel cloud retrievals of inhomogeneous clouds. In this study, we propose recurrent neural network-based transformers for cloud properties retrieval. Specifically, we develop Bidirectional Long Short Term Memory with Transformer for retrieving Cloud Optical Thickness (COT) and Cloud Effective Radius (CER) simultaneously. Through extensive experiments on multiple fractal cloud synthetic datasets with varying cloud top height, we demonstrate that our proposed models significantly outperform both physics-based approaches and state-of-the-art deep learning models for multi-view retrieval of cloud optical properties.

#### This poster was presented in 2022 UMBC Information Systems Student Research Sympothium 
