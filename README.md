# Image Segmentation of Breast Cancer Ultrasounds using U-Net Architecture 

This project utilizes a convolutional neural network to perform image segmentation on breast cancer ultrasound images, including benign, malignant, and normal scans. The project implements the U-Net architecture to encode and decode image data for accurate segmentation, aiming to predict target masks for cancerous areas. This work has the potential to assist healthcare professionals in early diagnosis, ultimately improving treatment plans and patient care

 The U-Net architecture is a CNN that is famous in biomedical imaging segmentation including, its ability to handle inputs with various size and ratios. During the down sampling, the encoder consists of a series of convolutional and pooling layers that reduce the spatial dimensions while increase feature maps. During the up sampling, a decoder consists of transposed convolutions to up sample the feature to the original image size. This produces the image segmentation map.

 ## Dataset 
 The Breast Cancer Ultrasound Image Dataset is a open source dataset created by Rudranarayan Baral. It contains a variety of ultrasound images of breast cancer patients which may come in various forms. This includes breast lesions such as ductal carcinoma in situ (DCIS), invasive ductal carcinoma (IDC), fibroadenomas, cysts and more. Each image in thedataset  is labeled and is split between the following directories below and each tumor has a corresponding target mask. The mask separates the ROI indicated in white as depicted in Fig.1 Benign tumor with Mask Target. Some images may have more than one associated mask which then is indicated by the label ending with ”mask 1”. An example is provided in Fig.2 Benign tumor image with multiple target mask from the dataset.
* Benign - 437 benign tumor patients
* Malignant - 210 malignant tumor patients
* Normal -133 total normal patients images
![Screenshot 2025-03-10 220826](https://github.com/user-attachments/assets/65dc4258-bef7-49cb-a0f9-923473e0dbed)

## Results 
![Screenshot 2025-03-10 221120](https://github.com/user-attachments/assets/2d4cfb43-5902-41ae-b916-0d4b08335209)
![Screenshot 2025-03-10 221130](https://github.com/user-attachments/assets/7a69bb13-f5a3-4e62-a9c0-7772c6d6681f)
![Screenshot 2025-03-10 221206](https://github.com/user-attachments/assets/be47a144-ee24-46b6-8a98-c7fac1462917)

## Development Tools 
Juptyer Notebook, Python, Tensorflow, Keras

## Contributers and Remarks
* Author Michelle Cheng 
* Professor Dr. Kandasamy Illanko 
