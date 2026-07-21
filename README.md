# 🚀 Object Detection using YOLOv8

A deep learning-based object detection project developed using **YOLOv8** to identify and localize objects in images. This project demonstrates the complete object detection pipeline, from dataset preparation and model training to evaluation and prediction.

---

## 📌 Project Overview

This project uses the **YOLOv8 (You Only Look Once)** algorithm to perform real-time object detection. The model is trained on an annotated dataset and evaluated using standard object detection metrics. The repository includes training notebooks, validation results, performance curves, and prediction outputs.

---

## ✨ Features

* Object detection using YOLOv8
* Custom dataset training
* Image preprocessing and annotation support
* Model validation and performance evaluation
* Prediction on unseen images
* Visualization of training results and detected objects

---

## 🛠️ Technologies Used

* Python
* YOLOv8 (Ultralytics)
* OpenCV
* NumPy
* Matplotlib
* Google Colab / Jupyter Notebook

---

## 📂 Dataset

This project is trained and evaluated using the **KITTI Object Detection Dataset**. The dataset contains real-world driving scenes with annotated objects such as cars, pedestrians, cyclists, trucks, and more, making it suitable for autonomous driving and computer vision applications. :contentReference[oaicite:0]{index=0}

### Dataset Sources

- **KITTI Dataset (YOLO Format):**  
  https://www.kaggle.com/datasets/shreydan/kitti-dataset-yolo-format

- **Original KITTI Dataset:**  
  https://www.kaggle.com/datasets/klemenko/kitti-dataset

### Dataset Structure

```text
dataset/
├── train/
│   ├── images/
│   └── labels/
├── valid/
│   ├── images/
│   └── labels/
├── test/
│   ├── images/
│   └── labels/
└── data.yaml
```

### Download the Dataset

1. Visit one of the Kaggle links above.
2. Download the dataset.
3. Extract it into your project directory.
4. Ensure the `data.yaml` file points to the correct dataset paths before training.

```

## 📂 Project Structure

```text
.
├── object_detection.ipynb
├── args.yaml
├── results.csv
├── results.png
├── confusion_matrix.png
├── confusion_matrix_normalized.png
├── BoxP_curve.png
├── BoxR_curve.png
├── BoxF1_curve.png
├── BoxPR_curve.png
├── labels.jpg
├── train_batch0.jpg
├── train_batch1.jpg
├── train_batch2.jpg
├── val_batch0_labels.jpg
├── val_batch0_pred.jpg
├── val_batch1_labels.jpg
├── val_batch1_pred.jpg
├── val_batch2_labels.jpg
├── val_batch2_pred.jpg
└── README.md
```

---

## 📊 Model Evaluation

The trained model is evaluated using the following metrics:

* Precision
* Recall
* F1-Score
* Mean Average Precision (mAP)
* Confusion Matrix

Training outputs include:

* Precision Curve
* Recall Curve
* F1 Curve
* Precision-Recall Curve
* Training Loss Graph
* Validation Predictions

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/object-detection-yolov8.git
cd object-detection-yolov8
```

### Install Dependencies

```bash
pip install ultralytics opencv-python matplotlib numpy
```

### Run the Notebook

Open the Jupyter notebook:

```bash
jupyter notebook object_detection.ipynb
```

or upload the notebook to **Google Colab** and run all cells.

---

## 📈 Results

The model successfully detects objects by predicting bounding boxes and class labels. Performance is visualized using precision, recall, F1-score, confusion matrix, and validation prediction images.

---

## 📚 Applications

* Autonomous Vehicles
* Smart Surveillance Systems
* Traffic Monitoring
* Industrial Automation
* Retail Analytics
* Robotics
* Security Systems

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, improve the project, and submit a pull request.

---

## 📄 License

This project is created for educational and learning purposes. You are free to use and modify it for non-commercial applications.

---

### ⭐ If you found this project useful, don't forget to star the repository!
