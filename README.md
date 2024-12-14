# ZARA - AI Personal Assistant  

## Description  
**ZARA** is a personal voice-controlled AI assistant developed using Python. It can perform a variety of tasks, such as answering questions, searching information, retrieving weather updates, controlling your PC, and much more using speech recognition and APIs.

## Features  
- **Voice Interaction**: Uses speech recognition to take commands and responds via text-to-speech.  
- **Internet-Based Tasks**:  
  - Wikipedia searches  
  - Real-time weather updates (OpenWeatherMap API)  
  - Retrieves headlines (Times of India)  
  - Opens Google, YouTube, Gmail, and Stack Overflow  
- **Utility Features**:  
  - Tells the current time  
  - Answers computational/geographical queries using WolframAlpha API  
  - Captures photos via webcam  
- **System Control**:  
  - Logs off or shuts down the computer  

## Technologies Used  
- **Python 3.x**  
- **Speech Recognition** (Google Speech-to-Text)  
- **Text-to-Speech**: pyttsx3  
- **Web Automation**: Webbrowser  
- **APIs**:  
   - OpenWeatherMap (Weather Updates)  
   - WolframAlpha (Question Answering)  
- **External Modules**:  
   - `ecapture` for camera usage  
   - Wikipedia API  

## Prerequisites  
1. Install Python 3.x  
2. Install required libraries:  
   ```bash
   pip install speechrecognition pyttsx3 wikipedia wolframalpha requests ecapture
   ```

3. Set up **APIs**:  
   - OpenWeatherMap: [Get API Key](https://openweathermap.org/api)  
   - WolframAlpha: [Get API Key](https://developer.wolframalpha.com/portal/)  

---

## Installation & Usage  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/mohammedabsal/Voice-Assistant.git
   cd Voice-Assistant
   ```

2. **Run the Program**  
   ```bash
   python zara.py
   ```

3. **Commands to Try**:  
   - *"Open YouTube"* - Opens YouTube in your browser.  
   - *"Search Wikipedia for Python"* - Returns Wikipedia summary for Python.  
   - *"Weather in Chennai"* - Provides weather updates for a city.  
   - *"What is the time?"* - Tells the current time.  
   - *"Take a photo"* - Captures a photo using your webcam.  
   - *"Who created you?"* - Know about the developer!  

---

## Example Output  
**Voice Command**: *"Weather in Chennai"*  
**Response**:  
```
Temperature in kelvin unit = 300.15  
Humidity (in percentage) = 80  
Description = scattered clouds  
```  

---

## Future Scope  
- Adding AI-based learning to make ZARA smarter.  
- Integrating task scheduling and reminders.  
- Support for more APIs like Spotify, WhatsApp, and Google Calendar.  

---
