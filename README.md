# YOLO-V4-Object-Detection
YOLO is short for You Only Look Once.


What’s new in YOLOv4?
What is YOLO?

YOLO is short for You Only Look Once. It is a real-time object recognition system that can recognize multiple objects in a single frame. YOLO recognizes objects more precisely and faster than other recognition systems. It can predict up to 9000 classes and even unseen classes. The real-time recognition system will recognize multiple objects from an image and also make a boundary box around the object. It can be easily trained and deployed in a production system.

Hands-on Data Science Course

Data Science is Fun is an end-to-end Data Science course that will teach you how to complete a Data Science project…

medium.com

How does YOLO work?

YOLO is based on a single Convolutional Neural Network (CNN). The CNN divides an image into regions and then it predicts the boundary boxes and probabilities for each region. It simultaneously predicts multiple bounding boxes and probabilities for those classes. YOLO sees the entire image during training and test time so it implicitly encodes contextual information about classes as well as their appearance.

YOLO v3 vs YOLO v4

Who developed YOLO?

YOLO is developed by Joseph Redmon. The introduction of the YOLO real-time object recognition system in 2016 is the cornerstone of object recognition research. This led to better and faster Computer Vision algorithms.

Who developed YOLOv4?

YOLO v4 is developed by three developers Alexey Bochkovskiy, Chien-Yao Wang, and Hong-Yuan Mark Liao.

Why Joseph Redmon is not developing YOLOv4?

He quit developing YOLO v4 because of the potential misuse of his tech. He especially referring to “military applications and data protection issues”. He ceases his research for Computer Vision because he found that the ethical issues involved were “become impossible to ignore”.

What is new in YOLOv4?

YOLOv4: Optimal Speed and Accuracy of Object Detection

YOLOv4’s architecture is composed of CSPDarknet53 as a backbone, spatial pyramid pooling additional module, PANet path-aggregation neck and YOLOv3 head.

CSPDarknet53 is a novel backbone that can enhance the learning capability of CNN. The spatial pyramid pooling block is added over CSPDarknet53 to increase the receptive field and separate out the most significant context features. Instead of Feature pyramid networks (FPN) for object detection used in YOLOv3, the PANet is used as the method for parameter aggregation for different detector levels.

What is an improvement in results?

YOLOv4 is twice as fast as EfficientDet (competitive recognition model) with comparable performance. In addition, AP (Average Precision) and FPS (Frames Per Second) increased by 10% and 12% compared to YOLOv3.
