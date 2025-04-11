# Drowsiness_detection
# Real-Time Object Detection using YOLOv5

This project performs **real-time object detection** using a **custom-trained YOLOv5 model** and a webcam feed. It captures frames through your webcam, runs object detection on each frame, and displays the output with bounding boxes and labels.

---

## Features

- Real-time object detection via webcam
- Fast inference using PyTorch and YOLOv5
- Supports custom-trained YOLOv5 weights
- Simple and lightweight Python implementation

---

## Technologies Used

- Python
- OpenCV
- PyTorch
- YOLOv5 (via `torch.hub`)

---

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/yolov5-object-detection.git
cd yolov5-object-detection
```
### 2. Install Dependencies

Install the required dependencies by running:

```bash
pip install -r requirements.txt
```
### 3. Download or Place the YOLOv5 Model Weights
Place your trained model file (last.pt) in the appropriate directory and update the path in the code if needed:

```python
model = torch.hub.load('ultralytics/yolov5', 'custom', path='your/path/to/last.pt')
```
## You can train your own model using the official YOLOv5 repository.

### 4.Run the Script
You can run the code from a .py file or Jupyter Notebook:

```python
python filename.py
```

### Author
S Mayur
GitHub: @mayur170804




