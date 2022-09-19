# Face-mask-detection-openCV

As the Block diagram shows a real-time video is taken as input which would be gone through Haarcascade files for the object detection. Haarcascade file is an Object Detection Algorithm used to identify faces in an image or a real-time video. The algorithm uses edge or line detection features and gives a lot of positive images consisting of faces, and a lot of negative images not consisting of any face to train on them. So, total of Three haarcascade files are used to detect faces, eyes, and mouths. While detection if the face is detected but, lips are not detected then it would show a warning message “Face mask not detected” and if both face and lips are detected but, the lips coordinates aren’t within face coordinates then again, the same message will be shown. Else one can say “face mask detected”. After detecting the face mask or not it will go for temperature detection with a condition of Body temperature and print messages accordingly.

Block Diagram
<img width="1663" alt="esd_proj block digram" src="https://user-images.githubusercontent.com/79366792/191059772-f07fa76f-0588-4ac8-98dc-f72044704686.png">


Final Report
[REV3-FACEMASK DETECTION USING OPENCV AND PYTHON(FINAL) (1).pdf](https://github.com/iriturj13/Face-mask-detection-openCV/files/9600530/REV3-FACEMASK.DETECTION.USING.OPENCV.AND.PYTHON.FINAL.1.pdf)
