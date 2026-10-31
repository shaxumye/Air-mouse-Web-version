# AirMouse

A browser-based air mouse that lets you control a virtual cursor using hand gestures and your webcam.

I built this project to experiment with hand tracking and see if a regular webcam could be used to interact with a computer interface without touching a mouse.

### Features

- Real-time hand tracking using MediaPipe.
- Move the cursor using your index finger.
- Click and drag using index and middle finger gestures.
- Drag windows around the playground.
- Draw on a scratchpad using hand movements.
- Switch between different brush colours.
- Interactive counter.
- Adjustable cursor smoothing.
- Open-palm gesture to pause and resume tracking.
- Camera on/off and layout reset controls.

### Built With

- HTML
- CSS
- JavaScript
- MediaPipe Hands

### Running Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/airmouse.git
   ```

2. Open the project folder.

3. Start a local server. If you have Python installed:

   ```bash
   python -m http.server 8000
   ```

4. Open `http://localhost:8000` in your browser.

5. Allow camera access when prompted.

That's it.

### Controls

| Action | Gesture |
|---|---|
| Move cursor | Move index finger |
| Click | Bring index and middle fingertips together |
| Drag window | Hold the gesture over a window title bar and move |
| Draw | Hold the gesture over the scratchpad and move |
| Pause / Resume | Open palm |
| Pause / Resume | Spacebar |
| Adjust sensitivity | Cursor smoothing slider |

### Notes

- A webcam and a working internet connection are required.
- Camera access requires HTTPS or localhost.
- Good lighting helps with hand detection.
- This is a browser-based playground. It doesn't control the actual desktop cursor.

### Project Structure

```text
airmouse/
└── index.html
```

Everything is currently contained in a single HTML file.

# AirMouse

A browser-based air mouse that lets you control a virtual cursor using hand gestures and your webcam.

I built this project to experiment with hand tracking and see if a regular webcam could be used to interact with a computer interface without touching a mouse.

### Features

- Real-time hand tracking using MediaPipe.
- Move the cursor using your index finger.
- Click and drag using index and middle finger gestures.
- Drag windows around the playground.
- Draw on a scratchpad using hand movements.
- Switch between different brush colours.
- Interactive counter.
- Adjustable cursor smoothing.
- Open-palm gesture to pause and resume tracking.
- Camera on/off and layout reset controls.

### Built With

- HTML
- CSS
- JavaScript
- MediaPipe Hands

### Running Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/airmouse.git
   ```

2. Open the project folder.

3. Start a local server. If you have Python installed:

   ```bash
   python -m http.server 8000
   ```

4. Open `http://localhost:8000` in your browser.

5. Allow camera access when prompted.

That's it.

### Controls

| Action | Gesture |
|---|---|
| Move cursor | Move index finger |
| Click | Bring index and middle fingertips together |
| Drag window | Hold the gesture over a window title bar and move |
| Draw | Hold the gesture over the scratchpad and move |
| Pause / Resume | Open palm |
| Pause / Resume | Spacebar |
| Adjust sensitivity | Cursor smoothing slider |

### Notes

- A webcam and a working internet connection are required.
- Camera access requires HTTPS or localhost.
- Good lighting helps with hand detection.
- This is a browser-based playground. It doesn't control the actual desktop cursor.

### Project Structure

```text
airmouse/
└── index.html
```

Everything is currently contained in a single HTML file.

### A Little About This Project
This started out of curiosity. I wanted to see if I could use a regular webcam to control a mouse with hand gestures, so I decided to build it myself.
It was a fun little project to work on, and a good way to learn more about hand tracking and computer vision.

