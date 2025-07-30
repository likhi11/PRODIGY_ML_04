
# Hand Gesture Recognition

This project aims to develop a hand gesture recognition model that can accurately identify and classify different hand gestures from image or video data. The goal is to enable intuitive human-computer interaction and gesture-based control systems.

## Dataset
The dataset used for training and evaluation is available at:
[LeapGestRecog - Kaggle](https://www.kaggle.com/gti-upm/leapgestrecog)

## Project Structure

```
hand_gesture_recognition/
│
├── models/               # Model definition and training scripts
├── utils/                # Utility functions for preprocessing and data handling
├── notebooks/            # Jupyter notebooks for experimentation
├── main.py               # Entry point to train and evaluate the model
└── README.md             # Project description and instructions
```

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/hand_gesture_recognition.git
cd hand_gesture_recognition
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Train the Model

```bash
python main.py --train
```

### 4. Evaluate the Model

```bash
python main.py --evaluate
```

## Requirements

- Python 3.8+
- TensorFlow or PyTorch
- OpenCV
- NumPy
- Matplotlib
