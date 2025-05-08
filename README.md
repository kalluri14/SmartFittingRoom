# SmartFittingRoom

**SmartFittingRoom** is an interactive web application that enables users to virtually measure body sizes and control the cursor using hand gestures. Built with **Python** and **Streamlit**, it leverages **OpenCV** and **MediaPipe** for real-time computer vision capabilities.

---

## 🧠 Features

- **Virtual Measurement Tool**: Estimate body measurements using hand landmarks, useful for virtual try-ons.
- **Gesture-Based Cursor Control**: Move your screen cursor using your fingertips like a virtual mouse.
- **Real-Time Webcam Feedback**: Live hand tracking with landmark visualization.
- **Clean, Web-Based UI**: Built using Streamlit for ease of use and rapid interaction.

---

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Computer Vision**: OpenCV, MediaPipe
- **Language**: Python 3.x

---

## 📁 Project Structure
</prev>
SmartFittingRoom/
├── frame_capture.py # Captures webcam frames
├── frame_draw.py # Draws hand landmarks and calculates distances
├── smart_fitting.py # Main Streamlit application
├── sizechart.jpg # Reference image for size estimation
└── README.md # Project documentation
<prev>
---

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/kalluri14/SmartFittingRoom.git
cd SmartFittingRoom
pip install -r requirements.txt
pip install streamlit opencv-python mediapipe
streamlit run smart_fitting.py
```
