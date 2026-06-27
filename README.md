# Speak It — Client-Side Text-to-Speech Reader

A clean, distraction-free, client-side Text-to-Speech (TTS) application built using vanilla HTML5, CSS3, and JavaScript. By leveraging the native Web Speech API (`window.speechSynthesis`), this application parses text locally in the browser with advanced multi-sentence chunk sequence streaming to bypass character length constraints.

## 🚀 Live Demo
[Insert Link to GitHub Pages Deployment]

## ✨ Features
* **Editor & Reading Modes:** Seamlessly switch between a full text editor and a distraction-free, high-legibility typographic canvas.
* **Live Token Tracking:** Sentence-by-sentence tracking and live word-level highlighting run synchronously across both views.
* **Starred Profiles:** Pin your favorite native system voices and dialects to a persistent global favorites section via `localStorage`.
* **Robust Engine Handling:** Customized segment streaming queues fix known Chromium/Safari platform execution stalls and long-gap pause dropouts.
* **Responsive Theme Engine:** Includes a unified Light/Dark mode wrapper matching current browser settings.

## 🛠️ Installation & Usage
Because this application is built entirely as a static client-side single file, it requires no package managers, build compilation steps, or external network dependencies.

1. Clone this repository:
   ```bash
   git clone [https://github.com/yourusername/speakit.git](https://github.com/yourusername/speakit.git)
