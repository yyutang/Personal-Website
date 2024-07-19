---
date: 2021T00:00:00+01:00
draft: false
title: "Traffic Sign Recognition Project"
jobTitle: "Traffic Sign Recognition"
company: "Python"
location: "The project is implemented in Python with OpenCV libraries. It's to recognize and identify the traffic signs in Canada. The project deals with image processing(shape and color processing) and image recognition(text and symbol recognition)"
duration: "2021"

---
### Traffic Sign Recognition

###### Abstract:
Traffic Sign Recognition is to recognize and identify the traffic signs in Canada. The project needs to deal with image processing (shape and color processing)  and image recognition (text and symbol recognition). The project delivers two segmentation programs that find the road sign in the image by colors and contours. After segments, a matching program is performed to compute the similarity with the dataset and present final recognition result.


###### Languages:
OpenCV is the primary use to achieve image reconstruction, image segmentation, and shape recognition in the traffic sign recognition system. The program is implemented in Python with OpenCV libraries, and the dataset is provided.

###### Approach:
Segmentation and Recognition.  
**1.Segmentation**: This is done by two approaches of segmentation - segmenting by colors, and segmenting by contours.  
**2.Recognition**:The next stage with the segmented single image of signs is the recognition. The recognition is to compare the segmented image with all traffic signs samples to calculate the highest probability of correspondence; which is the number of matching keypoints per sample.
