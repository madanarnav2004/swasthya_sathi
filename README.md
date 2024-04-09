

# Voice-Enabled Healthcare Chatbot with Regional Language Support

This repository contains code for a voice-enabled healthcare chatbot that supports regional languages. The chatbot utilizes ChatGPT for conversational generation, machine translation for English to Hindi translation, and speech recognition for transcribing Hindi speech inputs.

## Requirements
- PyTorch
- Transformers library from Hugging Face
- MarianMT model for English to Hindi translation
- Speech recognition model for Hindi transcription



## Features

- Voice-enabled: The chatbot supports voice input for a seamless user experience.
- Healthcare assistance: Provides medical assistance and information based on user queries.
- Regional language support: Supports regional languages such as Hindi for both input and output.
- Translation: Translates English responses to Hindi for users preferring regional languages.
- Speech transcription: Transcribes Hindi speech inputs to text for processing.

## Code Overview

- **ChatGPT Integration**: Utilizes the ChatGPT model from Hugging Face's model hub for generating responses to user queries.
- **Translation**: Implements a function for translating English text to Hindi using the Helsinki-NLP/opus-mt-en-hi model.
- **Speech Transcription**: Uses a pretrained speech recognition model for transcribing Hindi speech inputs to text.

## Landing Page

For a basic landing page demonstrating the features of this voice-enabled healthcare chatbot with regional language support, you can visit [here](https://framer.com/projects/Swasthya-Sathi-Website--HrbZHxrAusf3FNsBIGjR-9ws0I).
