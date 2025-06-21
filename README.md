# 🎙️ GIRI - Voice Desktop Assistant

GIRI is a personal voice-activated assistant built using Python. It listens to your commands and performs various tasks such as playing songs on YouTube, telling the time, fetching information from Wikipedia, telling jokes, and even opening applications like Google Chrome and VS Code.

---

## 🚀 Features

- 🎧 **Speech Recognition** – Listens to your voice and processes your commands.
- 🧠 **Natural Language Processing** – Understands basic voice commands.
- 🔊 **Text-to-Speech** – Replies with human-like speech using `pyttsx3`.
- 📺 **YouTube Integration** – Plays requested songs using `pywhatkit`.
- 📚 **Wikipedia Integration** – Answers questions about famous people.
- 🤣 **Joke Generator** – Tells random jokes using `pyjokes`.
- 🖥️ **App Launcher** – Opens apps like Google Chrome or VS Code.
- 🕒 **Time Inquiry** – Tells the current time.

---

## 📁 Project Structure

voice-desktop-assistant/
│
├── assistant.py # Main voice assistant logic
├── requirements.txt # List of dependencies
└── README.md # Project documentation (you're reading it!)


## 📦 Requirements

Install the following Python packages before running the assistant:

pip install SpeechRecognition pyttsx3 pywhatkit wikipedia pyjokes pyaudio
Note: On Windows, installing pyaudio may require a compatible .whl file. You can use:

nginx
Copy
Edit
pip install pipwin
pipwin install pyaudio
▶️ How to Run
Clone the repository:


git clone https://github.com/yourusername/voice-desktop-assistant.git
Navigate into the folder:


cd voice-desktop-assistant
Run the assistant:


python assistant.py
Speak your command when it says:

🎧 Listening...
🎤 Sample Voice Commands
"Play Shape of You"

"What's the time?"

"Tell me a joke"

"Who is Elon Musk?"

"Open Chrome"

"Open VS Code"

"Stop" or "Exit"

