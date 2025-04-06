# virtual_mouse
🖱️ Virtual Mouse Using Hand Gesture Recognition
This project implements a virtual mouse system that allows users to control the computer cursor using hand gestures. Built using Python, OpenCV, and MediaPipe
The system tracks hand landmarks via webcam in real time and maps specific gestures to mouse functions like cursor movement, clicking, and scrolling.
🚀 Features
- Real-time hand tracking with webcam
- Cursor movement using index finger position
- Left-click using index and middle finger gesture
- Right-click and scroll with gesture variations
- Touch-free control for hygienic and innovative interaction
🛠️ Technologies Used
- Python (https://www.python.org/)
- OpenCV (https://opencv.org/)
- MediaPipe by Google (https://mediapipe.dev/)
- [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/) – for automating mouse events
📁 Project Structure
├── virtual_mouse.py # Main script to run the virtual mouse 
├── requirements.txt # Python dependencies 
├── README.md # Project overview and usage instructions
🔧 Installation
1. Clone the repository
cd virtual-mouse
Install dependencies
pip install -r requirements.txt
Run the script
python virtual_mouse.py
Make sure your webcam is connected and facing your hand clearly.
🧠 How It Works
Uses MediaPipe Hands to detect 21 hand landmarks.

Tracks fingertip positions and identifies gestures.

Maps gestures to specific mouse actions using PyAutoGUI.
✨ Future Improvements
Add custom gesture training with TensorFlow

GUI toggle for enabling/disabling mouse features

Multi-hand gesture support
📄 License
This project is open-source and available under the MIT License.
Developed with ❤️ using AI and Computer Vision
