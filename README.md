Task 1: Built a voice assistant in Python 

Key Highlights:
A modular Python script that turns your device into a voice responsive assistant
Combines real time speech recognition with text to speech output
Handles common requests like greeting, time, date, and Wikipedia based queries
Clean structure with error handling and continuous listening loop

Libraries Used:
speech_recignition: Captures and interprets spoken input from the microphone
pyttsx3: Converts text responses into audible speech
datetime: Retrieves current time and date
wikipedia: Fetches short summaries for general queries from Wikipedia

Installation:
1. Install dependencies: pip install SpeechRecognition pyttsx3 wikipedia
2. Install Pyaudio for microphone input: pip install pipwin, pipwin install pyaudio
3. Run the program: python assistants.py

Error Handling: 
  Timeout detection if user does not speak
  Catches UnknownValueError if speech is unclear
  Handles internet/API failures gracefully
  Handles miscellaneous exceptions for robustness

Demo Preview:
![image](https://github.com/user-attachments/assets/6368ab88-c1f3-4a01-87a2-8142e35c3fa2)

Core Features:
Welcome Message: Greets the user on startup with a personalized touch
Voice Commands:
  hello - friendly greeting
  time - Announces current time
  date - Announces today's date
  what is <topic> - Fetches and reads a brief Wikipedia summary
Error Handling: 
  Timeout handling while listening
  Graceful responses to unrecognized audio or unavailable APIs
Continuous Listening Loop: Keeps the assistant active until manually stopped

Known Limitations:
  Might time out if no speech is detected
  Requires internet access for Wikipedia queries
  Handles only basic command patterns

Author:
Created by Safiya A, a Python Developer passionate about user friendly design, clean modular architecture, and creative tools that solve real world problems
