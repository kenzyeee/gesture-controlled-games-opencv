# Hand Gesture Controlled Games 🎮✋

This project uses real-time hand gesture recognition with OpenCV and MediaPipe to control games using a webcam.  
Hand gestures are mapped to keyboard inputs to enable hands-free gameplay.

---


## Tech Stack
- Python
- OpenCV
- MediaPipe Hands
- pydirectinput

---

## How It Works
1. Webcam captures live video feed
2. MediaPipe detects 21 hand landmarks
3. Finger positions are analyzed to recognize gestures
4. Gestures are mapped to keyboard inputs
5. Games respond in real time

---
## Demo

### Hill Climb Racing
![Hill Climb Demo](demo/hill%20climb.gif)

### Minion Rush
![Minion Rush Demo](demo/minions%20rush.gif)

## Gesture Mapping

### Hill Climb Racing
| Gesture | Action |
|------|------|
| Left Index Finger and Thumb touch | Accelerate |
| Right Index Finger and Thumb touch | Brake |

### Minion Rush
| Gesture | Action |
|------|------|
| Index Finger Movment | Move |


---

## Installation
```bash
git clone https://github.com/kenzyeee/gesture-controlled-games-opencv
cd gesture-controlled-games-opencv
pip install -r requirements.txt
