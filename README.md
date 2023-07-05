# bone_fracture_Detection
Training of an object detection model that detects various type of bone issues. This uses transfer learning of pretrained Yolov5 weights . The dataset was exported via roboflow.com.  This dataset was originally created by Jason Zhang, Caden Li. YOLOv5 is a proven and tested, production ready, state-of-the-art real-time object detection model. the model detects four classes, namely: angle, fracture, line, messed_up_angle. TensorBoard was used to gain insights into the model's performance, multiple runs of the model was also compared to analyze their differences.

# Objective
* Training a custom YoloV5 Object Detector
* Using transfer learning of pretrained YoloV5m and applying fine tuning
* Using YoloV5m to train a bone fracture detector on a custom dataset
* Freezing some layers and training the other layers up to the top layers

# Results


[Open in Google Colab]([https://colab.research.google.com/...](https://colab.research.google.com/drive/1tWiJxYvKfCXfq3lnMYqX_V12qkfmwyv-#scrollTo=jrnHbdWrTELr&line=1&uniqifier=1))


![screenshot](https://github.com/kennethugo/bone_fracture_Detection/assets/50516854/1dddf803-e542-4ce0-a5c4-7995d41c6cc5)

# Reference 
OpenCv University tutorial(LearnOpenCV) , roboflow.com

