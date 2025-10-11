# Mr. Scott's Block Fun 🎮

Educational block game (Tetris-style) for computer science students to test and advance their skills while learning about algorithms, UX, and data literacy.

## 🎯 Features

- **Classic Tetris Gameplay** with modern mechanics (SRS rotation, hold piece, ghost piece)
- **Adaptive Difficulty** that adjusts based on player performance
- **Educational Analytics** - Tracks detailed metrics for classroom data analysis
- **Multiple Game Modes** - Daily challenges, symbolic boost, and adaptive mode
- **Teacher Dashboard** - Export session data as CSV for analysis
- **Accessibility Options** - Colorblind palette and reduced motion support

## 🚀 Quick Start

### Option 1: Play Immediately (No Setup Required)

1. Simply open `index.html` in any modern web browser
2. Click "Start Game" or press Space/Enter
3. Start playing!

**Note:** The game will work without audio files or background images. You'll just have a simpler visual experience with no music.

### Option 2: Full Experience (With Assets)

For the complete experience with music and dynamic backgrounds:

1. Add audio files to the `audio/` directory (see `audio/README.md` for details)
2. Add background images to the `img/` directory (see `img/README.md` for details)
3. Open `index.html` in your web browser

## 🎮 How to Play

### Controls

- **Arrow Keys / WASD**: Move and rotate pieces
  - Left/Right (A/D): Move piece horizontally
  - Down (S): Soft drop (move down faster)
  - Up/Space: Rotate piece clockwise
- **Enter**: Hard drop (instantly place piece)
- **C / Shift**: Hold current piece for later
- **P**: Pause game

### Game Options

- **Ghost Piece**: Shows where your piece will land
- **Adaptive Mode**: Automatically adjusts difficulty based on your performance
- **Symbolic Boost**: Rewards accurate play with bonus points
- **Daily Seed**: Play the same random sequence each day
- **Queue Size**: Choose how many upcoming pieces to see (3-5)

### Scoring System

- **Line Clears**:
  - Single: 100 pts × level
  - Double: 300 pts × level
  - Triple: 500 pts × level
  - Tetris (4 lines): 800 pts × level
- **T-Spin**: Bonus points for advanced rotation moves
- **Back-to-Back**: 1.5× multiplier for consecutive difficult clears
- **Combo**: +50 pts per consecutive line clear
- **Perfect Clear**: +1800 pts for clearing the entire board

## 📊 Analytics & Data Export

This game is designed for educational use in data literacy courses. It tracks:

- **Lines Per Minute (LPM)** - Speed metric
- **Input Latency** - Response time measurements
- **Placement Accuracy** - Tracks mis-rotations and corrections
- **Advanced Moves** - T-Spins, Perfect Clears, combos
- **Session Duration** - Time played
- **Difficulty Progression** - Level reached

### For Teachers

1. Students can enter their ID before playing
2. All session data is stored locally in the browser
3. Click "Export CSV" to download all session data for analysis
4. Use the data in spreadsheets, Python, R, or other data analysis tools

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** - No build process or dependencies required
- **Responsive Design** - Works on desktop and tablets
- **Local Storage** - Game data persists in the browser
- **Progressive Enhancement** - Works without assets, better with them
- **Accessibility** - ARIA labels, keyboard navigation, screen reader support

## 📝 Browser Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- Local storage enabled (for saving data)

## 🎓 Educational Use

This game was created for computer science education and can be used to teach:

- **Algorithms**: Piece rotation, collision detection, line clearing
- **Data Structures**: 2D arrays, queues, state management
- **UX Design**: Controls, feedback, progressive difficulty
- **Data Literacy**: Analyzing gameplay metrics, identifying patterns
- **Statistics**: Performance trends, distributions, correlations

## 📄 License

Educational use - See code comments for attribution requirements.

## 🤝 Contributing

This is an educational project. Students can:
- Modify game parameters to experiment
- Add new features or game modes
- Analyze and visualize the collected data
- Create custom background images or music

## 🎨 Customization

The game is highly customizable through the options panel:
- Adjust lock delay timing
- Change queue size
- Enable/disable visual aids
- Set custom random seeds for reproducible games
- Toggle accessibility features

---

**Created by Mr. Scott** for classroom data literacy education. Enjoy the game! 🎮
