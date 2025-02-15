Math with Gestures ✋➕➖➗✖️

Math with Gestures is an AI-powered application that allows users to write mathematical expressions using hand gestures and get solutions in real-time. The project leverages computer vision, deep learning, and Google's Gemini AI to interpret handwritten mathematical equations drawn in the air and provides instant solutions.

🚀 Features

Hand Gesture Recognition: Uses OpenCV and MediaPipe-based cvzone.HandTrackingModule to detect hand gestures.
Air Drawing: Draw numbers and symbols in the air using your index finger.
Dynamic Gesture-Based Controls:
Raise the index finger to draw.
Raise the thumb to clear the canvas.
Show all fingers (except the pinky) to process the drawn equation.
Real-Time Processing: Captures video input from the webcam and overlays detected gestures on a virtual canvas.
AI-Powered Math Solver: Uses Google Gemini AI to interpret handwritten equations and return solutions.
Interactive Streamlit Interface: Displays live video feed and computed answers in a user-friendly UI.

🛠️ Tech Stack

Python
OpenCV (cv2)
cvzone (Hand Tracking Module)
NumPy
Google Generative AI (Gemini API)
PIL (Python Imaging Library)
Streamlit (for the web-based UI)

🎯 How It Works
Enable webcam access: The app starts capturing video input.
Draw with gestures:
Raise your index finger (pointing gesture) to draw numbers or symbols.
Raise your thumb to clear the screen.
Show all fingers except pinky to process the equation.

AI Processing:
The drawn equation is converted into an image.
The image is sent to Gemini AI for recognition and solution.
The result is displayed on the interface.
