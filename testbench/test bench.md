# Driver Monitor Testing Instructions

## 1. Python Version
Use Python 3.10 or 3.11.

## 2. Install Dependencies
Run:

python3.10 -m pip install mediapipe opencv-python simpleaudio

## 3. Run the Program
Navigate to the project folder:

cd driver-monitor

Then run:

python3.10 driver_monitor_mediapipe.py

## 4. How to Test

- Keep eyes open → text should display "Eyes OPEN"
- Close eyes briefly (<5 sec) → no alarm
- Close eyes for more than 5 second → alarm should trigger
- Press 'q' to quit

## 5. Expected Output
A webcam window will appear displaying real-time eye status.
