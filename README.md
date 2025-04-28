# YOLOv8 Live Object Detection

This project implements real-time object detection using a pre-trained YOLOv8 model (`yolov8n.pt`) in Python. It captures live video from a webcam, detects objects, and displays bounding boxes with labels and confidence scores.
📂 Features ✅ Real-time object detection from webcam

✅ Automatically downloads YOLOv8n model if not found

✅ Displays detected objects with labels and confidence scores

✅ Save detection frame with s key

✅ Quit with q key

📁 File Structure bash Copy Edit . ├── object_detection.py # Main detection script ├── yolov8n.pt # YOLOv8n model (auto-downloaded if not present) ├── detected_objects.jpg # Saved image from detection (when 's' is pressed) └── README.md # Project documentation 🙌 Acknowledgements Ultralytics for the YOLOv8 model

## How to run
- Install requirements: `pip install ultralytics opencv-python torch`
- Run: `python yolo_live_detect.py`
