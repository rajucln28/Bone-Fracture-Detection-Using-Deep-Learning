# 🦴 Bone Fracture Detection using YOLOv8

This project uses **YOLOv8**, a cutting-edge object detection model, to automatically detect bone fractures from X-ray images. It helps support fast, accurate diagnosis by localizing fracture regions with bounding boxes and confidence scores.



## 📌 Project Highlights

- ✅ Detects bone fractures in real-time X-ray images  
- 🔍 Trained and evaluated using YOLOv8 object detection  
- 📊 Provides detailed evaluation: mAP, Precision, Recall, F1-score, confusion matrix  
- 🌐 Flask-based web interface for easy image upload and visualization  
- 🧠 Uses deep learning for automated feature extraction and classification

🚀 Recommended Requirements (for training + inference):
OS: Ubuntu 20.04+ / Windows 11
CPU: Intel i7 or AMD Ryzen 7
RAM: 16 GB or more
GPU: NVIDIA GPU with CUDA support (e.g., GTX 1660, RTX 3060 or better)
VRAM: 6 GB+
Storage: 20 GB+ free
Python: 3.9 or higher
CUDA Toolkit: Version compatible with your PyTorch (optional but needed for GPU training)

📦 Software Dependencies
Python ≥ 3.8
pip ≥ 21.0
YOLOv8 (via ultralytics)
PyTorch (with or without CUDA)
Streamlit
OpenCV
Matplotlib, NumPy, scikit-learn

## 📁 Project Structure
BoneFractureDetection/
├── dataset/ # Labeled X-ray images & YOLO format labels
├── runs/ # YOLOv8 training logs and results
├── static/ # Uploaded & output images for the web app
├── templates/ # HTML templates (index.html, result.html)
└── README.md # Project documentation

---

## 🛠️ Tech Stack

- Python 3.x  
- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)  
- Flask (web framework)  
- OpenCV (image processing)  
- PyTorch (deep learning backend)  
- scikit-learn & matplotlib (evaluation and plotting)

---

## 🚀 How It Works

### 1. Training

Prepare your dataset in YOLO format and define it in a YAML config file.

📦 Installation
bash
Copy
Edit
# Clone this repository
git clone https://github.com/your-username/bone-fracture-detection-yolov8.git
cd bone-fracture-detection-yolov8

# Install dependencies
pip install -r requirements.txt


---

### ✅ Explanation:
- We **close the first Python code block** with ``` before starting `## 📦 Installation`.
- Then, we **open a new code block** just for the `bash` commands.

---

✍️ Authors
C LAKSHMI NARAYANA RAJU

