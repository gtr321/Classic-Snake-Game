# Classic-Snake-Game
A complete, single-file implementation of the classic Snake game, built using HTML, CSS, and vanilla JavaScript. This version is designed primarily for mobile devices, featuring touch controls and simple textures for visuals.

*A quick glimpse of the gameplay.*

## Features

*   **Single File Deployment:** The entire game (HTML, CSS, JS, Assets) is contained within one `.html` file.
*   **Mobile First Design:** Optimized viewport and touch controls for mobile play.
*   **Touch Controls:** Simple on-screen directional buttons.
*   **Keyboard Controls:** Basic arrow key and WASD support for desktop play/testing.
*   **Canvas Rendering:** Uses the HTML5 Canvas API for drawing the game elements.
*   **Textures & Graphics:** Simple embedded Base64 images for the snake, food, and background tile.
*   **Classic Gameplay:**
    *   Snake grows when it eats food.
    *   Game speed increases slightly as the score goes up.
    *   Game ends upon collision with walls or self.
*   **Score Tracking:** Displays the current score.
*   **Restart Functionality:** Easily restart the game after a game over.

## How to Play / Run

Since this is a single-file project, running it is straightforward:

1.  Download the `snake.html` file (or clone this repository).
2.  Open the `snake.html` file directly in your web browser.
3.  For the best experience (especially touch controls), open it on a mobile device or use your desktop browser's mobile device emulation mode (usually found in the developer tools - F12).

## Controls

*   **Mobile:** Use the on-screen directional buttons (▲, ▼, ◀, ▶) to change the snake's direction.
*   **Desktop:**
    *   Use the **Arrow Keys** (Up, Down, Left, Right) to change direction.
    *   Alternatively, use the **WASD** keys.
    *   Press **Enter** on the "Game Over" screen to restart.

## Technology Stack

*   HTML5 (Canvas API)
*   CSS3
*   Vanilla JavaScript (ES6+)
*   Base64 Data URLs (for embedding images and audio)

## Notes

<details><summary>Spoiler</summary>
**This was made by me for fun using AI.**
</details>

## Potential Future Improvements

*   Implement smoother animation using `requestAnimationFrame`.
*   Add high score tracking using `localStorage`.
*   Introduce different difficulty levels or speed settings.
*   Improve graphics and add more sound variety.
*   Add a pause button/functionality.
