# Helmet-detection-and-ANPR
<br>
This is project takes a video file as an input and detects if the person on 2-wheelers
are not wearing helmets and then take image of the riders and their registration plate.
</br>
<br>
Further the registration plate is fed to an OCR to extract the number plate in textual format.
</br>
<br>
In this project i am using yolv5 algorithm to detect rider, licence plate and riders head. Then using resnet50 image classifier, i classify wheather the rider is wearing a helmet or not. If not wearing a helmet then, it will save his licence plate number in a image folder, and also will capture rider image in a separate folder.
</br>
<br>
TLDR: this project takes a video input and gives plate numbers of those vehicles whose riders' weren't wearing a helmet.

# Contact harsh.zenith50@gmail.com for trained weight files and input video
