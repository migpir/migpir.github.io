Digital Sum Simulation





A fun, interactive web-based game where players enter a three-digit number (000–999) to calculate its digital sum (0–27) and flip a 10x5 grid of tiles representing U.S. states. Each tile reveals a random three-digit number, its digital sum, and profit/loss (P/L). Match your sum to win big! Built with HTML, CSS, and JavaScript, featuring a vibrant black and yellow theme with animations.

© MHP Digital Ventures LLC Copyright 2025

Features





Input: Enter a three-digit number (000–999) to compute its digital sum.



Tile Grid: 10x5 grid of U.S. state tiles, each with a random three-digit number (normal distribution, mean=499.5, σ=166).



Scoring: Earn +1 point per tile matching your sum, or +50 if no sum is set. Scores are saved to localStorage.



P/L Calculation: Tiles matching your sum show P/L = 250 - cost_table[sum] (green); others show cost_table[sum] (red).



Controls: "Flip All Tiles" to reveal results, "Reset" to clear score and input.



Design: Black gradient background with yellow text/borders, hover animations, pulsating tile borders, and mobile-friendly layout.

How to Use





Open the App:





Open wheel_of_fortune.html in a web browser (Chrome, Safari, etc.) on desktop or mobile.



Alternatively, visit the hosted version on GitHub Pages (replace username with your GitHub username).



Play the Game:





Enter a Number: Type a three-digit number (e.g., "661") in the input field. The digital sum (e.g., "Sum: 13") appears in the display.



Flip Tiles: Click "Flip All Tiles" to flip all 50 tiles, revealing state names, numbers, sums, and P/L (green for matches, red otherwise).



Check Score: Matching tiles add +1 to your score; no input adds +50. Scores persist across sessions.



Reset: Click "Reset" to clear the score, input, and display, and reset the grid.



Invalid Input: Non-numeric or out-of-range inputs (e.g., "abc", "1000") trigger an alert and clear the input.
