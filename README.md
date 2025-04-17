# Ticketless Parking System

This project implements a smart, ticketless parking access system that uses a Convolutional Neural Network (CNN) to recognize Dubai license plates and automate 
entry/exit logic. The system denies access to unauthorized plates (e.g., Abu Dhabi plates), supports free exit within a 10-minute window, and logs all vehicle interactions 
in a CSV file.

##### Features:
- Automatic number plate recognition using a trained CNN
- GUI built using Tkinter for image uploads and interaction
- Real-time logging of plate entries, exits, and payments in parking_log.csv
- Model achieves ~100% validation accuracy on Dubai plates

##### Access logic:
  - Dubai plate → Access granted
  - Dubai plate re-entry within 10 minutes → Free exit
  - Dubai plate after 10 minutes → Prompt payment via GUI
  - Abu Dhabi plate → Access denied
  - Machine learning-based detection (no OCR used)

###### Dependencies required:
- Python 3.10+
- TensorFlow
- Pillow
- NumPy
- Tkinter (comes pre-installed with Python)

### How to run the notebook:
- Run all the cells.

Doing the above would automatically train the model and launch the GUI.

## Links
1. YouTube Demonstration: https://youtu.be/_i18kU271ZU 
2. GitHub: https://github.com/reiamenezes2004/pde4433_coursework2_m00791121.git


