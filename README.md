# Whiteheart Voice Assistant

**Whiteheart** is a Python-based voice assistant with a modern graphical user interface (GUI) that can execute a variety of tasks through voice commands.  
It supports hotword detection, web searches, media playback, application launching, weather updates, jokes, facts, and even webcam photo capture — all in an interactive interface.  

---

## Features

- **Hotword Activation** – Responds to "Whiteheart" and similar variations.  
- **Wikipedia Search** – Retrieve concise summaries of any topic.  
- **YouTube Playback** – Search and play videos directly on YouTube.  
- **Math Calculations** – Perform quick calculations via voice.  
- **Entertainment** – Get random jokes and interesting facts.  
- **Weather Updates** – Check current weather for any city.  
- **Application Launching** – Open popular applications by name.  
- **Web Search** – Search Stack Overflow for programming queries.  
- **Photo Capture** – Take pictures using the system’s webcam.  
- **Modern UI** – Styled using `ttkbootstrap` for a sleek, dark-themed interface.  

---

## Requirements

- **Python**: Version 3.8 or later  
- **Dependencies**:  

```bash
pip install tkinter ttkbootstrap pyttsx3 SpeechRecognition requests randfacts wikipedia pillow opencv-python selenium webdriver-manager
```

- **Internet connection** for Wikipedia, jokes, weather, and YouTube features.  
- **Microphone** for voice input.  
- **Webcam** for photo capture (optional).  

---

## Project Files

- `voice_assistant.py` – Main application file.  
- `mic.png` – Microphone icon for GUI animation.  

---

## How to Run

1. Download or clone the project.  
2. Ensure `mic.png` is in the same directory as `voice_assistant.py`.  
3. Open a terminal in the project folder.  
4. Run the application:  

```bash
python voice_assistant.py
```

5. Wait for the greeting and then say **"Whiteheart"** followed by your command.  

---

## Example Commands

| Command | Function |
|---------|----------|
| `Whiteheart, tell me about Python` | Retrieves a Wikipedia summary of Python. |
| `Whiteheart, play relaxing music on YouTube` | Opens YouTube and plays relaxing music. |
| `Whiteheart, weather in London` | Provides current weather in London. |
| `Whiteheart, calculate 256 * 13` | Returns the result of the calculation. |
| `Whiteheart, tell me a joke` | Tells a random joke. |
| `Whiteheart, give me a fact` | Shares a random fact. |
| `Whiteheart, open Chrome` | Launches Google Chrome. |
| `Whiteheart, take a photo` | Captures a photo using the webcam. |
| `Whiteheart, search Stack Overflow for Python errors` | Opens a Stack Overflow search page. |
| `Whiteheart, exit` | Closes the assistant. |

---

## Notes

- Application names may differ depending on your operating system.  
- Avoid background noise for better voice recognition accuracy.  
- The assistant includes a short cooldown to prevent accidental repeated execution of identical commands.  

---

## License

This project is provided for personal and educational purposes. You may modify and distribute it with attribution.  
