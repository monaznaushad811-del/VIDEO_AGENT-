# VIDEO_AGENT-
Built an AI powered Video &amp; Meeting Assistant using RAG and LLMs that summarizes YouTube videos and meeting recordings, enables context aware question answering, and extracts key insights, action items, and important information from long form content.
# 🎥 VIDEO_AGENT

An AI-powered Video Processing Agent that transforms YouTube videos into actionable insights by automatically extracting audio, generating transcripts, translating content, and creating concise summaries.

## 🚀 Features

* 📺 Accepts YouTube video URLs
* 🎵 Downloads and extracts audio from videos
* 📝 Converts speech to text using AI transcription
* 🌍 Translates transcripts into Hindi
* 📄 Generates intelligent summaries
* 💾 Saves transcripts and summaries for future reference
* ⚡ Modular and scalable architecture

## 🛠️ Tech Stack

* Python
* yt-dlp
* FFmpeg
* OpenAI Whisper
* Deep Translator
* LangChain
* Mistral AI
* UV Package Manager

## 📂 Project Workflow

1. User enters a YouTube URL
2. Audio is downloaded from the video
3. Audio is converted into text using Whisper
4. Transcript is translated into Hindi
5. AI generates a concise summary
6. Results are saved locally

## 📁 Project Structure

```text
VIDEO_AGENT/
│
├── downloads/
├── transcripts/
├── summaries/
├── core/
├── main.py
├── requirements.txt
└── README.md
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/monaznaushad811-del/VIDEO_AGENT-.git
cd VIDEO_AGENT-
```

Create and activate a virtual environment:

```bash
python -m venv .venv
.venv\Scripts\activate
```

Install dependencies:

```bash
uv pip install -r requirements.txt
```

## ▶️ Usage

Run the application:

```bash
python main.py
```

Enter a YouTube URL when prompted.

The system will automatically:

* Download audio
* Generate transcript
* Translate content
* Create summary
* Save outputs

## 🎯 Future Enhancements

* Interactive Q&A on video content
* Vector Database Integration
* RAG-based Video Chat
* Web Interface using Streamlit
* Multi-language support
* Meeting recording analysis
* Video recommendation engine

## 👨‍💻 Author

Monaz Naushad

BCA | AI & Data Science Enthusiast

Building AI-powered applications using LLMs, Generative AI, and Agentic AI systems.

## ⭐ Support

If you found this project useful, consider giving it a star on GitHub.
