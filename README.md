# Road Object Detection with YOLO11

Detecting road users and traffic objects across diverse driving scenes in various weather conditions utilizing the pretrained YOLO11 Nano model. 

## Project Overview
This project establishes a computer vision pipeline for smart road monitoring. It evaluates object detection capabilities across three distinct scenarios:
* **Section A:** Static image analysis and raw dataset exploration.
* **Section B:** Frame-by-frame batch inference over recorded road video footage.
* **Section C:** Real-time stream processing from a live camera feed.

The model is configured to detect and track specific traffic-related COCO classes, including pedestrians, bicycles, cars, motorcycles, buses, trucks, traffic lights, and stop signs. Bounding boxes are dynamically color-coded by category for clear visual analysis.

## Environment & Dependencies
* Python 3.x
* `ultralytics` (YOLO11)
* `opencv-python` (cv2)
* `matplotlib`
* `kaggle` (for dataset acquisition)

## Dataset & Licensing Credits
Static image testing utilizes the **DAWN Dataset** (Broadening the driving scenes' visual data for adverse weather conditions). 
* **Source:** Kaggle (`shuvoalok/dawn-dataset`)
* **License:** This dataset is provided under the **CC-BY-NC-SA-4.0 License**.

Pre-recorded video inference uses a sample traffic video (`SampleVideo_LowQuality.mp4`) processed locally.

## Usage
1. **Clone the Repository:**
   ```bash
   git clone <your-repository-url>
   cd <your-repository-folder>

```

2. **Install Requirements:** Run the initial setup cell to install the required pip packages and authenticate the Kaggle API.
3. **Download Data:** Execute the dataset download cell to pull the DAWN dataset directly into your workspace.
4. **Run Inference:** Execute the notebook cells sequentially to process static images, run frame-by-frame video tracking, and initialize the live webcam feed.

## Contributors

* Yousuf Islam Mohamed
* Ali

```

```