# TensorFlowLite

### Tensors: 
Scaler: A single digit.
Vector: 
Matrix:
Shape: Shape refers to the dimension of the tensor.

### Resources
https://medium.com/@estebanuri/real-time-face-recognition-with-android-tensorflow-lite-14e9c6cc53a5


> Google ML kit - Face recognition <br>
> 

Face recognition system flow:
1. Input Image
2. Detect the face
2. Transform 
3. Crop


    First step, the face is detected on the input image.
    Second, the image is warped using the detected landmarks to align the face [4] (so that all cropped faces have the eyes in the same position).
    Third, the face is cropped, and properly resized to feed the recognition Deep Learning model. Also some image pre-processing operations are done in this step (e. g. normalizing and “whitening” the face)
    Fourth, the most “juicy part”, is the one depicted as “Deep Neural Network”. We are going to focus more on this step.
    
    
    The FaceNet approach:

FaceNet: A Unified Embedding for Face Recognition and Clustering.[2] FaceNet is a face recognition system developed in 2015 by researchers at Google that achieved the state-of-the-art results on a range of face recognition benchmark datasets (99.63% on the LFW). This work introduces the novel concept of triplet loss.




