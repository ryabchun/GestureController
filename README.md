# Gesture Controller

Gesture Controller is a Python application that allows you to control your computer using hand gestures captured through a webcam. It utilizes the Mediapipe library for hand tracking and gesture recognition and the PyAutoGUI library to execute commands based on the detected gestures.

## Features

- Recognizes hand gestures using Mediapipe hand tracking.
- Controls the mouse cursor and performs various actions using hand gestures.
- Adjusts system volume and brightness with pinch gestures.
- Supports multi-handedness for both left and right hands.

## Requirements

- Python 3.x
- OpenCV
- Mediapipe
- PyAutoGUI
- Screen-Brightness-Control
- Pycaw

Install the required libraries using the following command:
```bash
pip install opencv-python mediapipe pyautogui screen-brightness-control pycaw
```

## Usage

1. Clone this repository to your local machine.
2. Make sure your computer has a webcam connected.
3. Navigate to the project directory.
4. Run the `main.py` file:
5. 
  ```bash
  python main.py
  ```
5. The application will open a window showing the video feed from the webcam.
6. Place your hand in front of the webcam, and the application will recognize your hand gestures.
7. Use gestures to control the mouse, perform clicks, adjust volume, and brightness.

## Gesture Mapping

The application recognizes the following hand gestures:

- Fist: Perform a left-click.
- Index Finger Extended: Perform a right-click.
- Two Fingers Closed: Perform a double-click.
- V-Gesture: Move the mouse cursor.
- Palm Gesture: Stop any ongoing action.

To perform the pinch gesture for volume and brightness control:

- Use the thumb and index finger to perform a pinch gesture.
- Move the pinched fingers horizontally for volume control.
- Move the pinched fingers vertically for brightness control.

## Important Notes

- To exit the application, press the "Enter" key.
- If the application is not responsive, close the window or press "Ctrl + C" in the terminal to stop the program.

## Acknowledgments

The Gesture Controller project is based on Mediapipe and PyAutoGUI, which provide the hand tracking and automation functionality, respectively.

Happy gesture controlling! 🖐️🖥️

