# Blindness Detection

• Millions of people suffer from Diabetic retinopathy, the leading cause of blindness among working aged adults. Eye Hospitals in India hopes to detect and prevent this disease among people living in rural areas where medical screening is difficult to conduct. Currently, the technicians travel to these rural areas to capture images and then rely on highly trained doctors to review the images and provide diagnosis.

• A clinician has rated the presence of diabetic retinopathy in each image on a scale of 0 to 4, according to the following scale:

No DR - 0

Mild - 1

Moderate - 2

Severe - 3

Proliferative - 4

![img](https://user-images.githubusercontent.com/64200536/232227340-68398b4a-fc81-4364-bbe5-4f6697d1fc1c.jpg)

The task is to create an automated analysis system capable of assigning a score based on this scale.

• The images in the dataset come from different models and types of cameras, which can affect the visual appearance of left vs right. Some images are shown as one would see the retina anatomically (macula on the left, optic nerve on the right for the right eye). Others are shown as one would see through a microscope condensing lens (i.e. inverted, as one sees in a typical live eye exam).

• The goal here is to scale their efforts through technology; to gain the ability to automatically screen images for disease and provide information on how severe the condition may be. We shall be achieving this by building a Convolutional neural network model that can automatically look at a patient’s eye image and estimate the severity of blindness in the patient. This process of automation can reduce a lot of time thereby screening the process of treating diabetic retinopathy at a large scale.
