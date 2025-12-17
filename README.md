# Optimizing RGB Color Detection in Digital Images Using K-Nearest Neighbor (KNN)

This repository contains the source code and experiments for the research paper **“Optimizing RGB Color Detection in Digital Images Using K-Nearest Neighbor (KNN)”**.  
The work focuses on efficient and accurate RGB color detection using a lightweight supervised machine learning approach.

## 📌 Abstract
Color detection plays a vital role in computer vision, image processing, and human–computer interaction. This research applies the **K-Nearest Neighbor (KNN)** algorithm to optimize RGB color detection in digital images. A dataset of **865 labeled colors** with corresponding RGB and hex values is used for classification. By computing Euclidean distances in RGB space, the system achieves an accuracy of **93.089%** with an optimal **K = 5**. The approach demonstrates robustness under varying lighting conditions and supports real-time deployment using OpenCV.

## 🎯 Key Contributions
- KNN-based RGB color detection framework
- Feature extraction using RGB color histograms
- Optimization of K value for maximum accuracy
- Robust performance on normal, blurred, and masked images
- Lightweight and computationally efficient design

## 🧠 Methodology
- **Algorithm:** K-Nearest Neighbor (KNN)
- **Features:** RGB values (normalized)
- **Distance Metric:** Euclidean distance
- **Tools:** Python, OpenCV, NumPy, scikit-learn
- **Dataset Split:** 70% training, 30% testing

## 🧠 Methodology Overview
The proposed system uses the K-Nearest Neighbor (KNN) algorithm to classify colors based on RGB values. Each color is represented as a point in a three-dimensional RGB space, and classification is performed using Euclidean distance with majority voting.

<p align="center">
  <img src="colorpic.jpg" width="650"/>
  <img src="black 1.PNG" width="650"/>
  <img src="blur 1.PNG" width="650
</p>

*Figure: Workflow of the KNN-based RGB color detection system, including RGB feature extraction, distance calculation, and classification.*


## 📊 Results
- **Best Accuracy:** 93.089%
- **Optimal K Value:** 5
- **Detected Colors:**  
  Black, Blue, Brown, Forest Green, Green, Navy, Orange, Pink, Red, Violet, White, Yellow
- Reliable detection under blur and masking conditions


## 🚀 Applications
- Real-time color recognition
- Image editing and design tools
- Industrial automation
- Augmented & Virtual Reality
- Human–computer interaction systems

## 🔮 Future Work
- Multi-color detection within a single image
- Improved robustness under extreme lighting
- Integration of deep learning (CNNs, Transformers)
- Deployment in robotics and autonomous systems

## 👨‍💻 Authors
- **Mudasir Haider Baig Azad Khan**  
  Karakoram International University, Gilgit-Baltistan, Pakistan  
- **Asifa Zehra**  
  Karakoram International University, Gilgit-Baltistan, Pakistan  
- **Naeem Hussain**  
  Shenzhen University, Shenzhen, China  

## 📄 Paper
If you use this code, please cite the paper:  
**Optimizing RGB Color Detection in Digital Images Using K-Nearest Neighbor (KNN)**

## 📜 License
This project is intended for academic and research purposes.
