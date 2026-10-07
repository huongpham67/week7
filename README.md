# 🎮 Flappy Bird Game

A simple Flappy Bird game built with Flask and JavaScript, running on Chrome!

## 🚀 How to Run

### Step 1: Install Python dependencies
```bash
pip install -r requirements.txt
```

### Step 2: Run the Flask server
Open VS Code terminal and run:
```bash
python app.py
```

You should see:
```
🎮 Game running at http://localhost:5000
Open this URL in your Chrome browser!
```

### Step 3: Open in Chrome
- Open Chrome browser
- Go to: **http://localhost:5000**
- Start playing!

## 🎮 How to Play

- **Press SPACE** or **CLICK** to make the bird jump
- Avoid the green pipes
- Don't hit the top or bottom of the screen
- Each pipe you pass = 1 point
- Game ends when you hit an obstacle

## 📁 Project Structure

```
week7/
├── app.py                 # Flask server
├── requirements.txt       # Python packages
├── templates/
│   └── index.html        # Game HTML
└── static/
    ├── style.css         # Game styling
    └── game.js           # Game logic
```

## 🛠️ Technologies Used

- **Backend**: Python Flask
- **Frontend**: HTML5 Canvas, CSS, JavaScript
- **Browser**: Chrome (works on any modern browser)

## 📝 Features

✅ Smooth bird physics
✅ Procedurally generated pipes
✅ Score tracking
✅ Game over detection
✅ Restart functionality
✅ Responsive design

Enjoy! 🐦
