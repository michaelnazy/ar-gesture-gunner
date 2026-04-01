# AR Gesture Gunner 🔫🖐️

A web-based Augmented Reality (AR) shooter game built entirely with JavaScript, HTML5 Canvas, and Google's MediaPipe machine learning library. 

## Features
* **Real-time Computer Vision:** Uses MediaPipe Hands to track 21 3D landmarks on the user's hand through a standard webcam.
* **Gesture Recognition:** Aim with your index finger and "shoot" by dropping your thumb (calculating the pixel distance between the thumb tip and index finger base).
* **Magnetic Aim Assist:** Calculates the hypotenuse between the crosshair and targets to create a seamless "snap-to-target" lock-on effect.
* **Procedural VFX:** Features an HTML5 Canvas particle system for explosions, dynamic laser beams, and floating hit markers.
* **Synthesized Audio:** Uses the native Web Audio API to dynamically generate laser and shatter sound effects without external files.

## How to Play
To run this locally, you must use a local web server (like VS Code Live Server or IntelliJ's built-in server) due to browser security restrictions on webcam access.
1. Clone this repository.
2. Open the folder in your IDE.
3. Serve `index.html` on a local port.
4. Allow camera permissions, aim with your index finger, and drop your thumb to fire!
