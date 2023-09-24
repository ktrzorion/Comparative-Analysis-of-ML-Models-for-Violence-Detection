# Comparative-Analysis-of-ML-Models-for-Violence-Detection

## YoloV8s:

☻ Accuracy: 82%

☻ Description: YoloV8s is a lightweight object detection model that is based on the YoloV8 architecture. It is designed to be fast and efficient, while still maintaining a high level of accuracy. YoloV8s is trained on a massive dataset of images, and can detect a wide variety of objects, including people, vehicles, animals, and more.

☻ Strengths: YOLOv8 is known for its speed and accuracy in real-time object detection tasks. It can handle multiple object classes efficiently.

☻ Limitations: YOLO may not perform as well in cases where fine-grained details are crucial. Additionally, training YOLO models can be computationally expensive.

![Yolo Confusion Matrix](https://drive.google.com/file/d/1d0dz2taVF8OhxvLVfToQ0smE13R9VLna/view?usp=sharing)
![Yolo Precision-Recall Curve](https://drive.google.com/file/d/105QkKLHvGB4hAq_kzoxlxnMQApcJkf_o/view?usp=sharing)
![Yolo F-1 Confidence Curve](https://drive.google.com/file/d/1dQKQ0i_8OpAoZgeD6i3yw_p9vp2kNdw4/view?usp=sharing)
![Loss / Precision Charts](https://drive.google.com/file/d/1kZAQHFHJ4KEr3ZdbvgxDt4icyrwsKdnw/view?usp=sharing)
![Training Accuracy](https://drive.google.com/file/d/1Jk5IcBUSLh1sLCstaAaP_6HKmLiGVi1K/view?usp=sharing)
![Testing Accuracy](https://drive.google.com/file/d/1TawiSj8cwZd6k63gJlkz5WTrPLzIU0Jv/view?usp=sharing)
![Testing Accuracy](https://drive.google.com/file/d/1pgneqm0MDbhXSRXJ_ehf-6QMoxVOV6c9/view?usp=sharing)

## ResNet-50 on Binary Class Dataset:

☻ Accuracy: 60.77%
☻ Description: ResNet-50 is a convolutional neural network architecture that is based on the residual network architecture. Residual networks address the problem of vanishing gradients by adding shortcut connections between layers. This allows the network to learn deeper features and improve its accuracy. ResNet-50 has been shown to achieve state-of-the-art results on a variety of image recognition tasks, including object detection.
☻ Strengths: ResNet-50 is known for its ability to train very deep networks effectively, making it suitable for complex tasks. It has achieved state-of-the-art performance on various image classification benchmarks.
☻ Limitations: A binary classification accuracy of 60.77% may suggest that the model is struggling to learn the features specific to violence detection. Fine-tuning or using a more suitable architecture may be necessary.

## ResNet-50 on Multi-Label Class Dataset:

☻ Accuracy: 48.72%
☻ Description: ResNet-50 is a convolutional neural network architecture that is based on the residual network architecture. Residual networks address the problem of vanishing gradients by adding shortcut connections between layers. This allows the network to learn deeper features and improve its accuracy. ResNet-50 has been shown to achieve state-of-the-art results on a variety of image recognition tasks, including object detection.
☻ Strengths: ResNet-50 can still capture complex features, but its performance might be affected by the nature of the multi-label dataset and how well it's prepared.
☻ Limitations: An accuracy of 48.72% suggests that the model may have difficulty handling the multi-label nature of the data. Techniques like using appropriate loss functions or data preprocessing may improve performance.

## DenseNet:

☻ Accuracy: 87.01%
☻ Description: DenseNet is a convolutional neural network architecture that is designed to improve the efficiency of CNNs. It does this by connecting each layer of the network to all of the previous layers. This allows for more efficient feature extraction and reuse. DenseNet has been shown to achieve state-of-the-art results on a variety of image recognition tasks, including object detection.
☻ Strengths: DenseNet's dense connections allow it to capture features effectively, making it suitable for various computer vision tasks.
☻ Limitations: With an accuracy of 87.01%, DenseNet appears to be one of the top-performing models in your study. It might still benefit from further optimization or fine-tuning.

## MobileNet:

☻ Accuracy: 77.10%
☻ Description: MobileNet is another lightweight object detection model that is designed for mobile devices. It is based on a convolutional neural network (CNN) architecture, and uses depthwise separable convolutions to reduce the number of parameters and computations required. MobileNet is also trained on a large dataset of images, and can detect a wide variety of objects.
☻ Strengths: MobileNet is lightweight and can run on resource-constrained devices, making it suitable for edge computing scenarios.
☻ Limitations: While 77.10% is a respectable accuracy, it might not perform as well as deeper and more complex models like DenseNet in some cases.
