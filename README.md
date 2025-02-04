
## Virtual Trial Room with Pose Detection

This Python script implements a virtual trial room application that allows users to try on different shirts in real-time using a webcam feed. The application detects the user's pose and overlays selected shirt images onto the detected body. Additionally, it provides buttons for navigating through a collection of shirts.

### Prerequisites

- Python 3.x
- OpenCV (`cv2`) library
- CVZone library (including `overlayPNG` and `PoseModule`)

### Installation

1. Clone the repository 
2. Install the required libraries if not already installed:
   ```
   pip install opencv-python
   pip install cvzone
   ```

### Usage

1. Ensure your webcam is connected and functional.
2. Run the script `main.py`.
3. The application will open a window showing the webcam feed with virtual shirts overlaying the detected body.
4. Use the right and left buttons displayed on the screen to navigate through the collection of shirts.
5. Press the 'Esc' key to exit the application.

### Advisable to use Pycharm


References: 

https://www.youtube.com/watch?v=6C7R24-Ze10
