# VAD + Whisper
Dictate Text with In-Browser Voice Activation Detector and OpenAI Whisper Transcription. Single HTML.

Features:
- Transcribe what you say
- Copy Text button
- Send to ChatGPT button
- Start/Pause button

How it works:
- Voice Activation Detector Micro-AI runs locally in your browser to detect when you talk
    - https://www.vad.ricky0123.com/
- Each voice segment is send to OpenAI Whisper for transcription
- Each transcription is added to Textfield

Privacy + OpenAI Key:
- You have to put your OpenAI API-Key into the HTML
- Your OpenAI API-Key will be stored in LocalStorage (you only have to enter it once)
- Everything you say will be send to OpenAI
- To prevent evil-me from stealing your API-Key, inspect the HTML code and use a local copy of it
