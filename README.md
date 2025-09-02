# Attendance System using Face Recognition

A smart **automated attendance system** that uses **Face Recognition** to mark attendance in real-time. The system is built with **Python**, **Flask**, and the **face\_recognition library**, storing logs in CSV format and displaying results via a simple web interface.

---

## Features

* **Face Detection & Recognition** – Detects and recognizes registered faces.
* **Automated Attendance Logging** – Marks attendance directly into CSV files.
* **Web Interface** – Simple Flask app with HTML templates for interaction.
* **History Tracking** – Stores attendance records by date for easy retrieval.

---

##  Project Structure

```bash
Attendance-system-using-Face-recognition-main/
│── app.py                # Main Flask app
│── IMPLEMENTATION.txt     # Implementation notes
│── Attendance/            # CSV attendance logs
│   │── Attendance-03_14_23.csv
│   │── Attendance-04_03_23.csv
│   │── ...
│── templates/             # Frontend HTML files
│   │── home.html
```

---

## Installation & Setup

### Prerequisites

* Python 3.8+
* Required libraries:

  ```bash
  pip install flask face-recognition opencv-python numpy
  ```

### Run the Project

```bash
# Navigate to project folder
cd Attendance-system-using-Face-recognition-main

# Start the Flask app
python app.py
```

Now open your browser and go to  `http://127.0.0.1:5000/`

---

## Tech Stack

* **Backend**: Python (Flask)
* **Computer Vision**: OpenCV, dlib, face\_recognition
* **Frontend**: HTML (Jinja templates)
* **Data Storage**: CSV for attendance logs

---

## 📜 License

This project is licensed under the MIT License.

---
