# 📄 Dataset Description

This dataset contains feature vectors extracted from a collection of images using traditional computer vision descriptors. Each CSV file corresponds to a specific type of descriptor, grouped into color, texture, and shape categories. These descriptors are commonly used in image classification, pattern recognition, and content-based image retrieval (CBIR) tasks.

## 📁 Available files

- `color_hsv_hist.csv`: HSV color histograms  
- `color_lch_hist.csv`: LCH color histograms  
- `color_rgb_gch.csv`: Global RGB color histograms  
- `texture_glcm.csv`: GLCM-based texture features  
- `texture_blocks.csv`: Local statistical features (mean and standard deviation)  
- `texture_lbp.csv`: Local Binary Patterns (LBP) histograms  
- `shape_hog.csv`: Histogram of Oriented Gradients (HOG)  
- `shape_hu.csv`: Hu invariant moments  
- `shape_zernike.csv`: Zernike moments

## 📄 File structure

Each file contains:

- `image_name`: Unique image identifier  
- `class`: Label or category assigned to the image  
- `feat_0` to `feat_N`: Descriptor feature values
