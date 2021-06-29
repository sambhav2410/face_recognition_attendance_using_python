
# Attendance using Face Recognition
This project is made to take attendance in organisation(s). This uses face recognition to check a person's identity and mark him/her present or absent accordingly.

## Project Description
This is an **AI based project** working on the principle of **Computer Vision**. <br>
Using digital images and live feed it detects and **recognizes human face** and **mark their attendance**. <br>
The sole purpose of this model is to detect a person and add their details separately in Attendance list. <br>



## Advantages
- Instead of working on a single face, our model can **recognize multiple face in one frame**.
- Our model not only recognizes a face but also **mark attendance** of that recognized person.
- Our model update Attendance list **in real-time** (as soon as it recognizes a person).

## Real-time Usage
- Firstly, we **open the webcam** to take images of people present in front of the camera.
- Then we **check** each of them if they exist in our data or not. If not, they'll be called as 'Unknown'.
- After checking each of them with our data, we check that if they already **marked as present** or not. If not, we take that person's Registration no., Name & Entry time and mark them present.



## Output
|Registration_No.|Name|Entry_Date Entry_Time|
|---|---|---|
|19BCE10191|Hardik|2021-06-01 09:45:31.090713|
|19BCE10118|Sambhav|2021-06-03 15:45:21.483787|


## Result & Discussion
- This method can **detect multiple face** in one frame and can be easily used in a classroom or in an office.
- This system helps us to achieve desired results with **better accuracy** and less time consumption.
- The precision or the accuracy of face recognition of our model is almost **more than 90%**.



## Steps to Run
1. Fork this repo
2. Clone the forked repo to your local system
3. Install the following libraries: (in **Linux** or **macOS**)
   1. `cv2`
   2. `face_recogniton`
   3. `os`
   4. `math`
   5. `numpy`
   6. `datetime`
4. Add your image inside `imageData` folder in **format** -> `name.registration.jpg`, if adding more than one image of same person then **format** -> `name.registration.(0,1,2).jpg`, only after that it will recognize you. 
5. Run the code -> `code.py`
6. If it will recognise you, your attendance will be there in `Attendance.csv` file

**(Provide more than one image with different angle to get more accuracy)**

## Reference link
(Use this link when you unable to import **face_recognition** library) https://ourcodeworld.com/articles/read/841/how-to-install-and-use-the-python-face-recognition-and-detection-library-in-ubuntu-16-04


