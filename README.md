# 🚗 YOLOv5 + Deep SORT for Real-Time Car Detection, Tracking, and Counting (Top-View)

This repository implements a system for **detecting, tracking, and counting cars** from a **top-view perspective** using [YOLOv5](https://github.com/ultralytics/yolov5) for object detection and [Deep SORT](https://github.com/mikel-brostrom/Yolov5_DeepSort_Pytorch) for multi-object tracking.

<div align="center">
<p>
<img src="eval/input.gif" width="400"/> <img src="eval/output.gif" width="400"/> 
</p>

---

## 📌 Introduction

This project combines **YOLOv5 detection** with **Deep SORT tracking** to count cars in real time from aerial or surveillance footage.

- **Dataset preparation**  
 - Labeled over **300 top-view car images** using [Roboflow](https://roboflow.com/).  
 - Applied **data augmentation** to expand the dataset to **3,000+ images** for training.  

- **Detection**  
 - YOLOv5 was trained on the augmented dataset to detect cars from a top-down perspective.

- **Tracking**  
 - Implemented **Deep SORT**, which uses the **Kalman Filter** for robust multi-object tracking.  
 - Stored unique object IDs of detected cars and used the list length to count total cars.

---

## 🎥 Example Resources

- **Input Video:** [Watch here](https://drive.google.com/file/d/1V9ngeP0G8FSpe13VFjN62R4KWXADLMCM/view?usp=sharing)  
- **Dataset:** [Roboflow link](https://app.roboflow.com/ds/43Gg8QfcNi?key=WPiscHczVq)  
- **Model Weights:** [Download here](https://drive.google.com/file/d/1EnPc04tFzUDlWDAO4Oi7nDlSUp4MhFEB/view?usp=sharing)  
- **Output Video:** [Watch here](https://drive.google.com/file/d/1vLfAxRClU-iJnZjOkU6JVtlxsnC7JQIo/view?usp=sharing)  

---

## ⚙️ Technologies Used

- **YOLOv5** – Real-time object detection
- **Deep SORT** – Multi-object tracking with Kalman Filter
- **Roboflow** – Data labeling & augmentation
- **Python** – Implementation language

---

## 📚 References

- [YOLOv5 Repository](https://github.com/ultralytics/yolov5)
- [Deep SORT with YOLOv5](https://github.com/mikel-brostrom/Yolov5_DeepSort_Pytorch)

---
