# Jarvis-AI-Assistant

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

Jarvis-AI-Assistant is a Python-based personal AI assistant that simplifies daily tasks through voice commands. It combines advanced speech recognition and text-to-speech technologies to automate tasks, provide information, and improve productivity.

---

## 🎯 Features

- **Voice Commands:** Perform tasks like opening applications, searching the web, and setting reminders using natural voice inputs.
- **IoT Integration:** Control IoT devices with simple commands.
- **Web Automation:** Perform web searches and retrieve results instantly.
- **Text-to-Speech:** Jarvis responds in a natural, human-like voice.
- **Customizable:** Add new commands and functions as needed.

---

## 🚀 Installation

### Prerequisites
- Python 3.9 or above
- pip (Python package manager)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/omm-prog/jarvis-ai-assistant.git
   cd jarvis-ai-assistant
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the program:
   ```bash
   python jarvis.py

 ## 🛠️ How It Works

1. **Jarvis uses `SpeechRecognition`** to convert voice input into text.
2. Based on the command, Jarvis performs the following tasks:
   - Opens applications.
   - Conducts web searches.
   - Controls IoT devices.
   - Sets reminders or alarms.
3. Jarvis responds with appropriate output using `pyttsx3` for text-to-speech conversion.

---

## 🧩 Dependencies

The following libraries are required for this project:

- `speechrecognition`: For capturing and recognizing voice input.
- `pyttsx3`: For text-to-speech functionality.
- `wikipedia`: For fetching information from Wikipedia.
- `datetime`: For handling date and time functions.
- `os`: For system-level commands like opening files or applications.
- `webbrowser`: For automating web search.

To install all dependencies, run:
```bash
pip install -r requirements.txt
```
## 📝 Usage Examples

Here are some example commands you can give to Jarvis:

- **"Open Chrome"** → Opens the Google Chrome browser.
- **"Search for Python programming on Google"** → Performs a Google search for Python programming.
- **"Tell me the time"** → Reads out the current time.
- **"What is artificial intelligence?"** → Fetches and reads a summary from Wikipedia.



## 🔄 Ongoing Development

Jarvis-AI-Assistant is an actively developed project. New features and improvements are continuously being added. If you have any suggestions or would like to contribute, feel free to open an issue or submit a pull request!

Currently, the project is focusing on:

- Enhancing voice command recognition.
- Adding more automation capabilities, such as controlling IoT devices.
- Improving response accuracy and interaction speed.
- Integrating additional APIs for news, weather updates, and more.

Stay tuned for further updates! 😊

