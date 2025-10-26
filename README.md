# 👣 People Flow Detection & Heatmap Visualization

This project detects, tracks, and analyzes people’s movement in a video stream using **YOLO** and **OpenCV**.  
It also generates a **heatmap** to visualize areas of high and low activity — turning raw video data into actionable insights.

---

## 🎯 Features

- 🎥 **Real-time Detection** – Identify and track people frame by frame  
- 🔢 **Entry/Exit Counting** – Count how many people cross defined areas  
- 🌡️ **Heatmap Visualization** – Display movement density using color gradients  
- 🧠 **AI-Powered Tracking** – Uses YOLO + BoT-SORT for consistent tracking  
- 💾 **Video Output** – Saves both people-count and heatmap visualizations  

---

## 🧰 Tech Stack

| Component | Description |
|------------|-------------|
| **YOLOv11** | Object detection model (Ultralytics) |
| **BoT-SORT** | Multi-object tracking algorithm |
| **OpenCV** | Video processing and visualization |
| **Supervision** | Heatmap generation and detection management |
| **Python** | Programming language |

---

## 🚀 Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/<your-username>/people-flow-heatmap.git
cd people-flow-heatmap
```

## 🎬 Usage
### ▶️ People Counting

Detects and tracks people

Counts entries/exits across two virtual lines

Annotates frames with bounding boxes and counts


### 🔥 Heatmap Visualization

Detects people in each frame

Accumulates movement points

Generates a dynamic color-coded heatmap

