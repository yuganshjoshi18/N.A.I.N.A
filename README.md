# N.A.I.N.A | Neural Accessibility & Interaction for Natural Assistance

## Overview

N.A.I.N.A is an inclusive accessibility hub that integrates multiple assistive technologies into a single web interface. It provides functionalities like OCR (image and live camera), Text-to-Speech (TTS), Speech-to-Text (STT), Sign Language Recognition, Font Size Adjuster, and Screen Reader mode, aimed at improving digital accessibility for users.

## Features

* **OCR (Image to Text):** Upload an image and extract text using Tesseract.js.
* **Live Camera OCR:** Real-time text extraction from camera feed.
* **Text-to-Speech (TTS):** Converts typed text to audible speech.
* **Speech-to-Text (STT):** Converts spoken words into written text.
* **Sign Language Recognition:** Detects hand gestures using TensorFlow Handpose and Fingerpose.
* **Font Adjuster:** Increase, decrease, or reset font size for better readability.
* **Screen Reader Mode:** Reads highlighted text aloud.

## File Structure

```
project-root/
│
├─ index.html           # Main HTML file with embedded JS and CSS
├─ logo1.png            # Logo used in navbar
├─ README.md            # Project documentation

```

## Technologies Used


* **HTML5 & CSS3** - Structure and styling.
* **Tailwind CSS** - Utility-first CSS framework.
* **Tesseract.js** - OCR library for extracting text from images.
* **TensorFlow\.js** - Machine learning library for handpose detection.
* **Fingerpose** - Gesture recognition library.
* **Web APIs** - SpeechSynthesis, SpeechRecognition, and getUserMedia for TTS, STT, and camera access.

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/naiana-accessibility-hub.git
```

2. Open `index.html` in a modern web browser (Chrome/Edge/Firefox).

> **Note:** Some features like STT and camera OCR require HTTPS or `localhost` due to browser permissions.

## Live Link

[Access N.A.I.N.A](https://glittery-profiterole-34933f.netlify.app/)

## Usage

### OCR

* Upload an image using the file input.
* Click **Run OCR** to extract text.
* Progress is displayed while processing.

### Live Camera OCR

* Click **Start Live OCR** to access the camera.
* Click **Stop Live OCR** to end the session.
* Extracted text appears in the output box.

### Text-to-Speech

* Enter text in the input area.
* Click **Speak** to hear the text.
* Click **Stop** to cancel speech.

### Speech-to-Text

* Click **Start** to begin voice recognition.
* Click **Stop** to end recognition.
* Transcribed speech appears in the output box.

### Sign Language Recognition

* Allow camera access.
* Recognized gestures (Thumbs Up, Victory) will be displayed.

### Font Adjuster

* **A+**: Increase font size.
* **A-**: Decrease font size.
* **Reset**: Reset to default font size.

### Screen Reader Mode

* Click **Toggle Reader Mode**.
* Highlight text to have it read aloud.

## Browser Compatibility

* Tested on latest Chrome, Edge, and Firefox.
* Requires microphone and camera access for STT and live OCR.
* Works best on desktops and laptops.

## Future Improvements

* Mobile responsiveness enhancements.
* Additional gestures for Sign Language Recognition.
* Dark/Light mode toggle.
* Offline support for OCR and TTS.

## License

MIT License.

## Contributors

* Team HangmanxRooster 2025

---

This README provides all the necessary information for understanding, running, and contributing to the N.A.I.N.A Accessibility Hub project.

