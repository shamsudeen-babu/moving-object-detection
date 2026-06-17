# 🎯 Moving Object Detection

A beginner-friendly Python project that detects moving objects in real-time using a webcam.

---

## 📸 What It Does

When you run this project, it opens your webcam and watches for any movement.

- ✅ Captures the first frame as the background
- ✅ Compares each new frame with the background
- ✅ Draws a **green box** around any moving object
- ✅ Displays **"Moving Object Detected"** or **"Normal"** on screen
- ✅ Press **`Q`** to quit anytime

---

## 🛠️ Libraries Used

| Library | Why |
|--------|-----|
| `opencv-python` | To access webcam and process images |
| `imutils` | To resize video frames easily |
| `time` | To give the camera 1 second to warm up |

---

## ⚙️ Installation

Make sure Python is installed, then run:

```bash
pip install opencv-python imutils
```

---

## ▶️ How to Run

```bash
python moving_object_detection.py
```

> 💡 Make sure your webcam is connected before running!

---

