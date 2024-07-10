# Yolo-Object-detection-and-image-tracking-
Yolo Object detection and image tracking  for autonomous vehicles using CV and NN


# Final Project Report - Object Detection for Autonomous Vehicles

## Team Members
- Jashwanth Neeli
- Megha Kaavali Mahadevappa

## Abstract
The detection and tracking of objects in computer vision systems is crucial, with applications across various industries such as surveillance, autonomous navigation, and vehicle navigation. Advances in computing power and public datasets have propelled this field forward. This paper discusses various algorithms for object detection and tracking.

## Introduction
Object detection in computer vision is essential for identifying and locating objects within an image, crucial for applications like autonomous driving and security systems. This involves using neural networks trained on labeled images to recognize and locate objects, a process enhanced by architectures like YOLOv9.

## Dataset
We utilized a custom video streaming dataset featuring various vehicles and street elements from Chicago streets. This was supplemented by the COCO dataset with 80 labels, converted into 3500 images for training and validation.

## Literature Review

### Object Detection Methods
- **Background Subtraction:** Useful in static camera setups by analyzing pixel value differences.
- **Optical Flow:** Focuses on motion patterns to detect and track moving objects.
- **Complementary Methods:** Combines frame differencing, optical flow, and background subtraction to enhance detection accuracy.

### Object Classification Methods
- **Motion-Based:** Classifies objects based on movement, useful in dynamic environments but struggles with stationary objects.
- **Texture-Based:** Utilizes texture information for classification, effective in detailed surface analysis.
- **Shape-Based:** Employs pattern-matching algorithms to classify objects based on shape.

### Object Tracking Methods
- **Point Tracking:** Tracks objects by tracking specific features across frames.
- **Kernel Tracking:** Uses a kernel template for tracking, suitable for dynamic environments.
- **Silhouette Tracking:** Uses object models to track objects, effective in surveillance.

## Methodology
- **YOLOv9 Performance:** The latest YOLO model shows remarkable accuracy on the COCO dataset and improved performance on specialized datasets like Roboflow 100.
- **Advancements in Object Detection:** Developments include anchor-free detection methods and efficient Non-Maximum Suppression processes.

## Results
Significant improvements in loss metrics and mean Average Precision scores demonstrate the model's enhanced ability to detect and classify objects accurately.

## Observations on Class Performance
Some classes like buses showed low performance, likely due to limited dataset instances and high visual similarity with other classes.

## Conclusion
Continual optimization of object detection models is essential to address performance variability across different object classes.

## Future Work
- Implement lane line detection.
- Evaluate the model's performance on lane line detection regarding recall, precision, and map score.

## Technologies Used
- **YOLOv9:** For object detection
- **COCO Dataset:** For training and validation

![image](https://github.com/jashwanthneeli/Yolo-Object-detection-and-image-tracking-/assets/76511089/6be51242-b1fc-4860-9f46-650aa90f4edc)


![image](https://github.com/jashwanthneeli/Yolo-Object-detection-and-image-tracking-/assets/76511089/2007085c-a962-461d-afad-9f88439d0730)
