# DETECTION PAPILLEDEMA ON FUNDUS CAMERA WITH CNN


## PROJECT OBJECTIVES
The project objectives are grouped under the following 3 main headings:
### Obtaining Retina Image Without Using Mydriatics:
The fundus camera device used to obtain Retina Image in Eye Clinics uses visible light to obtain retinal image. The use of visible light causes miosis (shrinking of the pupil) in the eye while the device is shooting, and mydriatics are used to prevent this. Mydriatics are drugs that act by stopping mydriasis in patients for a short time, and it is necessary to wait for half an hour after administration for them to take effect. Within the scope of the project, it is aimed to obtain Retina Image without the use of mydriatics in order to prevent this process and facilitate the treatment. It is planned to use infrared lights and infrared camera technology that do not trigger miosis in the eye.
### Designing a Retina Image Capture Device that Does Not Require Expertise to Use:
Retina Images are images that are frequently needed in other polyclinics apart from Eye Polyclinics. Fundus camera devices used to obtain retinal images are expensive and portable devices that require technical expertise. This situation makes it impossible to obtain Retina Image in outpatient clinics other than Eye Polyclinics and unnecessarily increases the demand for consultation to the Eye Polyclinics of other polyclinics, thus increasing the density of the Eye Polyclinics unnecessarily. Within the scope of the project, it is aimed to develop a portable Retina Image Capture Device that is easy to use in other outpatient clinics, does not require technical expertise and is portable.
### Papilledema Detection Using CNN Structure:
Papilledema is a serious and important finding especially for Neurology Outpatient Clinics. As a matter of fact, detection of papilledema in examination requires experience or Ophthalmology expertise in terms of eye findings. For this reason, a large number of patients are sent to the Eye Polyclinic for consultation every day for papilledema examination, and this creates a serious workload. In project scope; It has been determined as the primary and main goal to integrate a CNN infrastructure that will provide decision support to the physician about the findings of papilledema in the designed device.


## Project Method:
The following methods will be used within the scope of the project:
### IR (Infrared) Imaging Method:
Miosis develops in the eye where visible light is intense. The miosis reflex is a reflex stimulated only by visible light and is insensitive to IR or UV light. IR Imaging Methods is a very common imaging method, especially in heat mapping technologies, and IR light is used to obtain images.
### Data Engineering:
Data Engineering is the process of extracting meaningful data and analyzes by analyzing and classifying already obtained, irregular big data. It will be used in the project for sorting and processing the Retina Images taken in the past in appropriate groups. In this context, the numPy library, which is an open source, n-dimensional matrix processing library, the pandas library that facilitates data preprocessing, and the matplotlib libraries that provide detailed functions for data visualization were preferred for the project.
### Image Processing:
Image Processing methods are methods used to manipulate digital images or to produce meaningful analysis. In the project, the images obtained for the past will be used to break the linearity of the datasets and to process the snapshots obtained during device use according to the CNN outputs. LGPL v3.0 licensed openCV library is planned to be used for image processing.
### CNN (Convolutional Neural Network – Convolutional Neural Networks):
CNN structure is a Deep Learning methodology developed to enable the use of Artificial Neural Networks structure discovered as a result of the development of Machine Learning functions and redesign for Deep Learning. In the project, it will be used to teach Papil Edema examination to the computer. In this context, it is planned to use the Keras library, which provides auxiliary functions for the use of the CNN structure.
### OCT:
It is one of the devices used to obtain detailed and more precise findings about the eye examined in OCT Eye Polyclinics. It will be used to correlate the Retina Images to prove the accuracy of the data obtained in the project.
### Fundus Camera:
It is used to obtain retinal image in fundus examination. Fundus Camera devices specially developed for this purpose are used in Eye Polyclinics. In the project, Retina Images taken with the Fundus Camera obtained in the past will be used as a dataset.

## Project Method
1) Data Collection:
Data will be obtained from Necmettin Erbakan University Meram Medical Faculty Hospital. For this, first of all, the necessary Ethics Committee approvals will be obtained from Meram Medical Faculty and in order to consider patient privacy, no patient's personal data will be shared within the scope of the project, only necessary data will be collected. Required data:
 
a) Retina Images Obtained by Fundus Camera:
Retinal imaging is routinely provided with a fundus camera in the clinic. Images taken with a fundus camera are kept in the hospital database in digital environment. Normal and papilledema images in the database will be selected by the ophthalmologist and included in the project (Figure-1). Since the device planned to be turned into a product in the project will also receive fundus camera-like images, it was deemed appropriate to process retinal images obtained with a fundus camera within the scope of the project.


<p align="center">
  <img width="560" height="300" src="https://user-images.githubusercontent.com/29986610/211399043-4ecbb2a4-d498-4d48-8b05-bfc05ada0859.png">
</p>
 
Figure-1: Eye view of the patient with “A” normal, “B” papilledema from the images taken with the fundus camera
