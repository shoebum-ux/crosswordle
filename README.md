# Cross Wordle

An interactive word puzzle game where players guess two intersecting 5-letter words that share a common center letter.

## Game Features

- **Direct Grid Input**: Click on any cell in the cross-shaped grid to start typing
- **Smart Navigation**: Use Tab to move through cells logically, Arrow keys for directional movement
- **Real-time Validation**: Immediate feedback on word validity
- **Color-coded Feedback**: Wordle-style color coding (green=correct, yellow=present, gray=absent)
- **On-screen Keyboard**: Visual keyboard with color feedback matching your guesses
- **Guess History**: Track all your previous attempts with detailed feedback
- **Responsive Design**: Works on desktop and mobile devices

## How to Play

1. **Objective**: Guess two 5-letter words that intersect at the center cell
2. **Input**: Click any cell in the grid to start typing
3. **Navigation**: 
   - Use Tab to move through cells in logical order
   - Use Arrow keys for directional movement
   - Click directly on any cell to jump there
4. **Submit**: Click "Enter Guess" or press Enter when both words are complete
5. **Feedback**: Letters are color-coded after each guess:
   - 🟩 Green: Letter is correct and in the right position
   - 🟨 Yellow: Letter is in the word but wrong position  
   - ⬜ Gray: Letter is not in the word

## Project Structure

```
CrossWordle/
├── index.html          # Main HTML structure
├── style.css           # Styling and layout
├── script.js           # Game logic and word dictionary
└── README.md           # This file
```

## Running the Game

1. Navigate to the CrossWordle directory
2. Start a local server:
   ```bash
   python3 -m http.server 8000
   ```
3. Open your browser and go to `http://localhost:8000`

## Technical Details

- **Word Dictionary**: Contains 12,000+ valid 5-letter English words
- **Pre-calculated Pairs**: Valid word combinations that intersect properly
- **Responsive Layout**: Two-column design that fits any screen
- **Keyboard Support**: Full keyboard navigation and input handling

## Recent Updates

- Added comprehensive word validation
- Implemented direct grid cell interaction
- Enhanced keyboard navigation
- Improved visual feedback and UI
- Added guess history with color coding
- Fixed alignment and responsive design issues

Enjoy playing Cross Wordle! 