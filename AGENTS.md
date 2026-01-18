# The Brownish Bomber

A vanilla HTML/CSS/JS boxing workout generator web application with a retro 1970s boxing gym aesthetic.

## Overview

This is a single-file web app (`brownish-bomber.html`) that generates randomized boxing workouts. It features:

- **Workout Generator**: Creates structured workouts with warm-up, technique rounds, burnout rounds, and conditioning
- **Configurable Settings**: Adjustable combo length (3-8) and number of rounds (4-15)
- **Interactive Timer**: Full-screen timer overlay with boxing bell sounds, pause/resume, and skip functionality
- **Punch Combinations**: Generates combos using standard boxing notation (1=jab, 2=cross, 3-6=hooks/uppercuts, plus defensive moves)

## Tech Stack

- Pure HTML/CSS/JavaScript (no frameworks or build tools)
- Embedded SVG logo
- CSS variables for theming
- Web Audio API for boxing bell sounds

## Key Features

- **Workout Time Display**: Shows estimated workout time in the generate button (3 min/round + 1 min rest)
- **Progressive Difficulty**: Combo length increases through technique rounds
- **Classic Combos**: Includes traditional boxing combinations (1-1-2, 1-2-3-2, etc.)
- **Responsive Design**: Works on mobile and desktop

## File Structure

```
brownish-bomber.html  - Single-file application (all HTML, CSS, JS inline)
AGENTS.md             - This file
```

## Workout Structure

1. **Warm-Up**: 2 rounds of 3 exercises each (1 min per exercise)
2. **Technique**: Main rounds with progressive combo complexity (3 min + 1 min rest)
3. **Burnout**: High-intensity rounds alternating MAX SPEED / MAX POWER
4. **Conditioning**: Strength/cardio exercises (45 sec work, 15 sec rest)
