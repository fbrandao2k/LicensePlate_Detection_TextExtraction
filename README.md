# LicensePlate_Detection_TextExtraction

Based on the Udemy course: ![YOLOv8, Train Custom Dataset, Object Detection, Segmentation, Tracking, Real World 17 + Projects & Web Apps in Python](https://www.udemy.com/course/yolov8-the-ultimate-course-for-object-detection-tracking/?utm_source=adwords&utm_medium=udemyads&utm_campaign=LongTail_la.EN_cc.BR&campaigntype=Search&portfolio=Brazil&language=EN&product=Course&test=&audience=DSA&topic=&priority=&utm_content=deal4584&utm_term=_._ag_112130202440_._ad_467215026440_._kw__._de_c_._dm__._pl__._ti_aud-2297301418005%3Adsa-1007766171312_._li_9217442_._pd__._&matchtype=&gad_source=1&gclid=Cj0KCQjwj4K5BhDYARIsAD1Ly2ob30_806U1E4g9s2P3xlHKqpn1GkUzKFMkj54bLi7W_D8RbAfryoQaAhKOEALw_wcB&couponCode=LETSLEARNNOW)

Methods of detecting license plates of vehicles and extracting its text/number information.

## Features

### Dataset
The dataset is from Roboflow, https://universe.roboflow.com/moin/car_license_plates/dataset/2, with 712 images, train set, valid set, and test set.

### Training
Trained with the number of epochs = 100, weight = yolov8m.pt

### Detection from images
![license_plate_detection](https://github.com/user-attachments/assets/35538943-9354-4a36-b068-653c65744e70)

### Extracting text / number
The easyocr package is used to extract the license plate information.

### Detection from videos
Import a video, then run the detection routine.
