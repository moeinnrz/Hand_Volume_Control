# 🖐️ Hand Volume Control using Python

This project is a touchless volume controller that uses hand gestures to adjust the system volume in real-time. Built using **Python**, **OpenCV**, **MediaPipe**, and **pycaw**, it allows users to control volume by simply moving their thumb and index finger closer or farther apart in front of a webcam.

## 🎯 Features

- 👋 Real-time hand tracking using MediaPipe
- 🔊 Volume control using distance between thumb and index finger
- 🎥 Live camera feed with visual feedback (lines, landmarks, volume percentage)
- ⚙️ Works with system volume on Windows (via `pycaw`)
- 🖥️ Smooth and responsive UI with OpenCV

## 🧰 Technologies Used

- Python 3.x
- OpenCV
- MediaPipe
- pycaw
- comtypes

## 🖼️ Demo

![img4](https://github.com/user-attachments/assets/5c64ba9a-92b6-459b-8d79-b068e8cbffca)

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/HandVolumeControl.git
cd HandVolumeControl
```
2. Install Dependencies

Make sure you have Python installed, then run:
```
pip install opencv-python mediapipe pycaw comtypes
```
3. Run the App
```
python Volume_Hand_Contorl.py
```
Then show your hand to the webcam — bring your thumb and index finger closer to decrease volume, and move them apart to increase it!

📌 Notes

  * Only works on Windows, because pycaw is Windows-specific.

  * Make sure your webcam is working properly.

  * You can exit the program anytime by pressing the Q key.

🔒 Permissions

  * The program changes system volume — make sure your script has the proper access.
  * Some systems may require running the Python script as administrator for full control.
📁 File Structure
```
HandVolumeControl/
├── Volume_Hand_Contorl.py
└── README.md
```
  * Some systems may require running the Python script as administrator for full control.
