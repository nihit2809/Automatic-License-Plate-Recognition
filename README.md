# Automatic-License-Plate-Recognition
Used YOLOv5s6 model for localizing the license plate and Google's PYTESSERACT for performing OCR over the localized image
<br>
<br>
Used the UFPR-ALPR dataset<br>
	This dataset, called UFPR-ALPR dataset, includes 2700 fully annotated images (over 30,000 LP characters) from 150 vehicles in real-world scenarios where both the vehicle and the camera (inside another vehicle) are moving.

	The images were acquired with three different cameras and are available in the Portable Network Graphics (PNG) format with a size of 1,920 × 1,080 pixels. The cameras used were: GoPro Hero4 Silver, Huawei P9 Lite, and iPhone 7 Plus. 

	The dataset is split as follows: 65% for training and 35% for validation. 

	Every image has the following annotations available in a text file: the camera in which the image was taken, the vehicle’s position and information such as type (car or motorcycle), manufacturer, model and year; the identification and position of the LP, as well as the position of its characters.

Acknowledgement:<br>
R. Laroca, E. Severo, L. A. Zanlorensi, L. S. Oliveira, G. R. Gonçalves, W. R. Schwartz, and D. Menotti, “A Robust Real-Time Automatic License Plate Recognition Based on the YOLO Detector” in 2018 International Joint Conference on Neural Networks (IJCNN), July 2018, pp. 1–10.
<br>
<br>
The trained model can used using the yolov5s6.pt file.
<br>
<br>
Image used for inference: <br>
<br>
![alt text](https://github.com/nihit2809/Automatic-License-Plate-Recognition/blob/main/Test-Data/test-image.jpg)
<br>
Cropped Image<br>
![alt text](https://github.com/nihit2809/Automatic-License-Plate-Recognition/blob/main/Test-Data/cropped-image.jpg)<br>
<br>
<br>
The final output was **"KP22ONL"**
