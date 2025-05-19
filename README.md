# Voice & Text Translator Streamlit App

**Description**
A Streamlit-based application that takes live voice or audio files, transcribes speech to text, translates into five languages (English, Spanish, French, German, Chinese Simplified), and outputs both translated text and synthesized audio.

**Features**
- Input modes: live mic (placeholder), audio file upload, manual text entry
- Automatic speech-to-text using `SpeechRecognition`
- Translation via `googletrans`
- Speech synthesis using `gTTS`
- Downloadable translated audio

**Getting Started**
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/voice-translate-streamlit.git
   cd voice-translate-streamlit
Install dependencies:
  pip install -r requirements.txt
Run the app:
  streamlit run app.py
