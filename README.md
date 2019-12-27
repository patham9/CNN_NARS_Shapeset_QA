**CNN-based detection of geometric shapes in images, and reasoning-based question answering**

This project uses OpenNARS for visual question answering about shape drawings, utilizing output from a Convolutional Neural Network which was trained on a variation of Shapeset.

See the report for more information: https://github.com/patham9/CNN_NARS_Shapeset_QA/blob/master/ML_ProjectReport_PatrickHammer.pdf

And for the implementation (using TensorFlow for the CNN + OpenNARS), have a look at: https://github.com/patham9/CNN_NARS_Shapeset_QA/blob/master/ShapeDetector.ipynb

Author: Patrick Hammer

Email: patrick.hammer@temple.edu

Example:

![Detections of shape classes and properties](https://user-images.githubusercontent.com/8284677/71529455-b4d51100-28dc-11ea-8388-2c64b951e955.png)

Question to OpenNARS: What shape is the filled rectangle left to?

```<(*,(&,[filled],rectangle),{?1}) --> leftOf>?```

Answer: <(*,(&,[filled],rectangle),{shape2}) --> leftOf>. %1.00;0.32% 
