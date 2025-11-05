# Image Processing 

This repository documents a comprehensive set of **Image Processing experiments** designed to explore digital image fundamentals, enhancement, restoration, compression, morphological processing, and feature extraction techniques.
Developed using **Python**, **OpenCV**, and **NumPy**, the modules focus on both spatial and frequency domain operations.



##  **Objective**

gaining practical understanding of core and advanced image processing concepts — from image enhancement and restoration to segmentation and feature extraction — and builded a reusable toolkit for computer vision experimentation.


##  **Technologies Used**

* **Python**
* **OpenCV (cv2)**
* **NumPy**
* **Matplotlib**


## **MODULE 1 – Image Enhancement & Segmentation**

### **1. Image Arithmetic & Logical Operations**

* Perform addition, subtraction, bitwise AND, OR, NOT on images.
* Understand pixel-level transformations.

### **2. Kernel-Based Enhancement**

* Apply smoothing and sharpening filters.
* Explore spatial filtering using custom kernels.

### **3. Gray-Level Slicing**

* Highlight specific intensity ranges with/without background.

### **4. Histogram Equalization**

* Enhance image contrast and compare results across images.

### **5. Spatial Filtering (Low & High Pass)**

* Apply averaging, Gaussian, and Laplacian filters.
* Observe differences in noise suppression and edge preservation.

### **6. Frequency Domain Filtering**

* Perform FFT-based filtering.
* Implement low-pass & high-pass filters in the frequency domain.

### **7. Edge Detection & Segmentation**

* Detect lines, points, and edges using Sobel, Prewitt, and Canny operators.
* Perform region-based and morphological segmentation (thresholding, watershed).


## **MODULE 2 – Image Restoration, Morphological Processing & Feature Extraction**

### **1. Image Restoration**

* Remove noise using mean, median, and Wiener filters.
* Implement constrained least squares and geometric mean filters.
* Evaluate PSNR and MSE before and after restoration.

### **2. Image Compression**

* Implement lossless compression: Huffman coding, Golomb coding, and LZW.
* Analyze compression ratios and efficiency.

### **3. Morphological Image Processing**

* Perform **Erosion**, **Dilation**, **Opening**, **Closing**.
* Explore **hit-or-miss**, **thinning**, **thickening**, and **skeletonization**.
* Apply morphological operations for noise removal and shape analysis.

### **4. Feature Extraction**

* Compute **boundary**, **region**, and **whole-image descriptors**.
* Extract **background**, **boundary preprocessing**, and **connected components**.
* Calculate **texture features** using **GLCM (Gray Level Co-occurrence Matrix)**.
* Extract **principle components** for dimensionality reduction.
