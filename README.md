# colab-speech-text-assistant

Colab Speech-to-Text Assistant is a lightweight Python-based voice interaction prototype designed to run in Google Colab. It demonstrates speech recognition, command handling, and basic assistant-style responses in a notebook-friendly environment.

## Features
* Speech-to-text transcription using Python
* Fully compatible with Google Colab
* Simple command-based interaction
* Displays real-time recognized text
* Handles Indian Standard Time (IST) formatting

## Installation
### Clone the repository
* git clone https://github.com/krth-007/colab-speech-text-assistant.git
### Move into the project folder
* cd colab-speech-text-assistant
### Install required dependencies
* pip install -r requirements.txt

* Open the notebook or Python file in Google Colab.
* Run all cells to initialize the assistant.

## Usage

* Run the script or execute all notebook cells in Google Colab.
* Provide voice input when prompted.
* The system processes the audio and prints the transcribed text in the output.
* If a supported command is detected, the assistant responds accordingly.

## Example Output
* Listening...
Input: What is the time?
Assistant: Current time in IST is 20:45

* Listening...
Input: Hello
Assistant: Hello! How can I help you?

## Tech Stack

* Python 3
* SpeechRecognition
* Google Colab
* datetime module
