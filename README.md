🔥 InfraredVisionAI
📌 Overview
InfraredVisionAI is a deep learning-based object detection system optimized for infrared and thermal imagery. Using YOLOv5 integrated with PyTorch and Roboflow, the project enables high-accuracy detection in low-light or no-visibility environments, making it suitable for surveillance, search & rescue, and military applications.

🚀 Features
🌌 Infrared & Thermal Image Support for low-light conditions.

⚡ YOLOv5-based Object Detection with real-time inference.

📈 Custom Dataset Training via Roboflow integration.

🔄 Preprocessing & Augmentation to enhance thermal data.

🖥️ Deployment Ready for edge devices with ONNX/TorchScript export.

🛠️ Tech Stack
Framework: PyTorch, YOLOv5

Data Pipeline: Roboflow API

Languages: Python

Libraries: OpenCV, TorchVision, NumPy

📲 How It Works
Clone YOLOv5 repo and install dependencies.

Import custom infrared dataset via Roboflow.

Train YOLOv5 models on thermal imagery.

Evaluate using mAP, precision-recall metrics.

Deploy for real-time infrared object detection.

🔧 Installation
bash
Copy
Edit
git clone <repo-link>
pip install -r requirements.txt
📌 Future Enhancements
Integrate YOLOv8 for improved accuracy.

Support multi-sensor fusion with RGB + IR data.

Build a lightweight edge deployment pipeline.

📜 License
MIT License
