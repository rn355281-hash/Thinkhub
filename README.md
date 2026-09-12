# 🎵 Two-Hand Media Volume Control

TEAM NAME: APEX

Team Members: 
Member 1: Prajesh S Pillai (Lourdes Matha College of Science and Technology)
Member 2: Rohit Nair (Lourdes Matha College of Science and Technology)

## About the Project

**Two-Hand Media Volume Control** is a simple and interactive project that allows users to control the media volume using hand gestures instead of using the keyboard, mouse, or physical volume buttons.

The main idea behind this project is to make volume control more convenient and touch-free. By using a camera to detect the user's hands, the system measures the position and movement of the hands and converts the gesture into a volume level.

For example, the user can move their hands closer together or farther apart to decrease or increase the volume. This makes the interaction feel more natural and gives the project a hands-free approach to controlling media.

## 🎯 Objectives

* To control media volume using hand gestures.
* To reduce the need for physical buttons or keyboard controls.
* To make media interaction more natural and user-friendly.
* To demonstrate the use of computer vision and hand tracking.
* To create a simple real-time system that responds to hand movements.

## ⚙️ How It Works

The project uses the device's camera to capture the user's hand movements.

The basic process is:

1. The camera captures the video in real time.
2. The system detects the user's hands.
3. Important points on the hands are identified using hand-tracking technology.
4. The distance between the two hands is calculated.
5. This distance is converted into a corresponding volume level.
6. The system changes the computer's media volume based on the detected gesture.

So, instead of manually pressing the volume buttons, the user can simply use their hands.

## 🖐️ Gesture Control

The main gesture used in the project is based on the distance between the two hands.

* **Hands down → Lower volume**
* **Hands up → Higher volume**

The exact gesture behaviour can be adjusted depending on how the project is implemented.

## 🛠️ Technologies Used

* **HTML,CSS3,JavaScript** – Main programming language
* **OpenCV** – Used for camera input and image processing
* **MediaPipe** – Used for real-time hand detection and tracking
* **Computer Vision** – Used to interpret hand movements
* **OS/System Audio Controls** – Used to change the actual media volume

## 📁 Project Structure

```text
Two-Hand-Media-Volume-Control/
│
├── peak.html
├── README.md
```

> The file names may be different depending on the final project structure.

## 🚀 How to Run the Project

Step 1. Clone the project

Download the project files to your computer.

Step 2. Allow camera access

When the program starts, make sure camera permission is enabled. The camera is required to detect the hand gestures.

Step 3. Control the volume

Place both hands in front of the camera and change the distance between them to control the media volume.

## 💡 Why This Project?

We normally control media volume using buttons, keyboards, touchscreens, or a mouse. While these methods work well, they require physical interaction.

This project explores a different approach by using something we already have with us — our hands. It also gives a practical example of how computer vision can be used to create more natural human-computer interactions.

The project is not intended to replace normal volume controls. Instead, it demonstrates how hand tracking can be connected with everyday computer functions.

## 🔮 Future Improvements

There are several ways this project could be improved in the future:

* Add separate gestures for **volume up and volume down**.
* Add gestures for **play, pause, next, and previous**.
* Improve hand detection in low-light environments.
* Add support for more operating systems.
* Reduce unwanted volume changes caused by accidental movements.
* Add a visual volume indicator on the screen.
* Allow users to customize their own gestures.
* Improve the smoothness and responsiveness of volume changes.

## ⚠️ Limitations

The project depends on the camera being able to clearly see the user's hands. Poor lighting, excessive distance from the camera, or objects blocking the hands can affect detection accuracy.

The performance may also vary depending on the computer's camera, processing power, and the implementation of the hand-tracking system.

## 👨‍💻 Conclusion

The **Two-Hand Media Volume Control** project shows how computer vision can be used to create a simple hands-free interaction system. By tracking both hands and converting their movement into volume control, the project provides a more interactive way of controlling media.

More importantly, this project helped us understand how technologies such as OpenCV and hand tracking can be combined with normal computer functions to create practical applications.

---

## 📌 Note

This project was developed as an experimental/academic project to useless projects 3.0


LINK => https://peak-roan.vercel.app/
