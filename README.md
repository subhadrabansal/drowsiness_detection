#drowsiness_detection
This is a system which can detect the drowsiness of the driver using CNN - Python, OpenCV. The aim of this is system to reduce the number of accidents on the road by detecting the drowsiness of the driver and warning them using an alarm.
## The Dataset
The dataset which was used is a subnet of a dataset from(https://www.kaggle.com/datasets/dheerajperumandla/drowsiness-dataset)<br />
it has 4 folder which are <br />1) Closed_eyes - having 726 pictures<br />
                          2) Open_eyes - having 726 pictures<br />
                          3) Yawn - having 725 pictures<br />
                          4) no_yawn - having 723 pictures<br />

## The Convolution Neural Network
![CNN](https://user-images.githubusercontent.com/16632408/159187014-4bc4b70e-98d6-4313-873f-997ded2eff27.png)

## Accuracy 
We did 50 epochs, to get a good accuracy from the model i.e. 98% for training accuracy and 96% for validation accuracy.
![Graph](https://user-images.githubusercontent.com/16632408/159187004-92a72662-ddfe-471d-8bd6-65a3593a70a1.png)

## The Output 
1. Open Eyes<br />
![Open_eyes](https://user-images.githubusercontent.com/16632408/159187179-b557ab8e-fb8c-4408-850b-417893014f8c.png)
2. Close Eyes<br />
Here we detect wheater the eyes are closed and count the number of frames for which the eyes were closed (which is 10 frame) greater then that the Alarm will ring and the WARNING sign is displayed.
![Closed_eyes](https://user-images.githubusercontent.com/16632408/159187305-68cbdee3-8325-4216-85e3-7dbb66a429fb.png)
