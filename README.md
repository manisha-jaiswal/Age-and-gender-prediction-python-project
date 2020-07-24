# Age-and-gender-prediction-python-project
python project

        Automatic age and gender prediction has become relevant to an increasing amount of applications , particularly since the size of social platforms and social media.

        In this project , I had used deep learning to accurately identify the gender and age of a person from a single image of a face . The predicted gender may be one of               ‘Male’ and ‘Female’ and the predicted age may be ranges(0-2),(4-6),(8-12),(15-20),(25-32),(38-43),(48-53),(60-100)(8 modes of final softmax layer).

        It is very difficult to accurately guess an exact age from a single image because of factors like makeup , lighting , obstructions and facial expressions and so, I made        this a classification problem instead of making it one of regression

Objective
        
        In proposed system, we will use the concept of Deep Learning to accurately identify the gender and age of a person from a single image of a face. 

        We are trying to make more interactive and understandable system. 

        It is very difficult to accurately guess an exact age from a single image because of factors like makeup , lighting , obstructions and facial expressions .And so we make         this a classification problem instead of making it one of regression

        For this project, we will use the Adience Dataset servers as a benchmark for face photos and is inclusive of various real world imaging conditions like noise , lighting        , pose and appearance

       Age and Gender Prediction System demonstrates better results of predict age and gender than traditional systems and shows robustness to changes. The system can be used          world wide at 

                 Social Media Platform

                Product selling

                Patient monitoring system.

Advantages

        User Friendly 
  
        Efficient
  
        Helpful for information gathering
  
        Less time consuming
  
Functional Requirements
    
    Face detection- We must have a clear image or a system with good quality of webcam.
              
              TECHNIQUE:opencv_face_detector.pbtxt, opencv_face_detector_uint8.pb
              
              METHOD:Neural network-For face detection, we have a .pb file- this is a protobuf file (protocol buffer); it holds the graph definition and the trained weights of                 the model. We can use this to run the trained model. And while a .pb file holds the protobuf in binary format, one with the .pbtxt extension holds it in text                      format. These are TensorFlow files.

    Age detection
              Technique:age_deploy.prototxt, age_net.caffemodel

    Gender detection
              Technique:gender_deploy.prototxt, gender_net.caffemodel
              
              For age and gender, the .prototxt files describe the network configuration and the .caffemodel file defines the internal states of the parameters of the layers.                  a few pictures to try the project on.

Software and Library Requirements
      
      SOFTWARE REQUIREMENTS
              
              Operating system : Windows 10
              Coding Language : Python 3.7
              Tools : Opencv , CNN 
              Dataset : Adience Dataset
              Platform : Python IDLE, windows command prompt
    
    LIBRARY REQUIREMENTS
            
            Libraries : cv2 , os , tkinter ,Math , argparse


