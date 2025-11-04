<div align="center">
  <img src="database/_README/ivy-header.gif" alt="Ivy Header"/>
</div>

# About

**Ivy** (Intelligent Voice for You) is a virtual assistant designed to provide a natural interaction experience without relying on complex cloud-based AI systems. It combines speech recognition, hotword detection, and intelligent command processing to create a responsive digital companion that runs primarily on your local machine

It is more than a virtual assistant it’s a concept of a personal digital companion that blends usability with human-like interaction. It incorporates lightweight NLP (Natural Language Processing) features and intelligent command interpretation for a smoother experience unlike traditional voice assistants, Ivy focuses on offline lightweight intelligence prioritizing usability, speed, and human-computer interaction rather than complex AI systems

> Created as a final requirement for my Software Engineering 1 Class

---

<br>
<img src="database/_README/introducing.GIF" width="100%">
<br>

## Installation

It's recommended to use a virtual environment to keep dependencies isolated

```bash
py -m venv venvivy
```

Then, if you have installed to activate

```bash
# On windows:
venvivy\Scripts\activate
# On MacOS/Linux:
source venvivy/bin/activate
```

Install the required dependencies

```bash
pip install -r requirements.txt
```

If you are on VSCode you must select the python interpreter that you locally created e.g. "venivy"

## User Guide

1. Launch the Python application with run.py
2. Ensure microphone and speaker access are enabled
3. Speak a command or chat to Ivy
4. The assistant executes the task and responds via voice output

## Features

- **Voice-Enabled Interface** - Fully voice-controlled interaction for hands-free operation
- **User-Friendly UI** - Clean and intuitive interface designed for accessibility and ease of use
- **Real-Time Processing** - Executes commands and fetches information instantly
- **Offline Mode Support** - Basic functionalities available without an internet connection.
- **Multi-Platform Compatibility** - Works seamlessly across different operating systems and devices
- **Database Integration** - Stores user preferences, command history, and configurations
- **Error Handling System** - Provides feedback and correction suggestions for failed commands
- **Face Authentication** - Secure user access using facial recognition
- **Hotword Detection - "Hey, Ivy"** - Always listening for activation keywords _(API ENABLED)_

## Commands

This are the current active commands, some few commands are API enabled:

- **Dynamic News Updates** - Fetches real-time news through API integration
- **Voice-Controlled Web Access** - Open any website using voice commands linked to a database
- **App Launch via Voice Commands** - Instantly open apps using database-backed voice control
- **Smart Assistant Info** - Provides current time, date, and weather for any location
- **Wikipedia-Powered Knowledge Base** - Retrieves information directly from Wikipedia
- **Intelligent Speech Correction** - Detects and fixes unclear or mispronounced words
- **YouTube Search Integration** - Search and browse YouTube using voice commands
- **Personalized Greetings** - Welcomes the user intelligently based on context
- **Communication Suite** - Supports voice calls, video calls, and text messaging
- **Device Information** - Displays detailed device status such as CPU usage, memory usage, battery percentage, and mores

If you wish to add a command just go to lib/main/command.py

## Some commands and features demo

### Face authentication:

This face authentication is available at lib/auth/\* , if you wish to generate a face authentication for youself go to trainer.py and generate a face authentication for yourself

<img src="database/_README/face-authentication.gif" width="70%">

#### Device information:

<img src="database/_README/device.gif" width="70%">

### Voice features:

<img src="database/_README/voice-feature.gif" width="70%">

### Web Commands:

<img src="database/_README/web.gif" width="70%">

### App Commands:

<img src="database/_README/app.gif" width="70%">

## Credits

This project was **influenced by** the repository  
**[projectswithdigambar/jarvis](https://github.com/projectswithdigambar/jarvis)** on GitHub.

While the design and concept draw inspiration from that work, this version introduces distinct enhancements such as offline capabilty, modified logic, and improved features, all developed within the span of one week

---

</br>
<div align="center">
  <img src="database/_README/ivy-footer.png" alt="Ivy Footer"/>
</div>
