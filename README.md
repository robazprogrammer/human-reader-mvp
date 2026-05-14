# Human Reader MVP

An AI-assisted accessibility reader for webpages and documents with natural voice playback, citation cleanup, and listening-focused text extraction.

## Overview

Human Reader MVP is an AAEL Labs prototype designed to improve the listening experience for people who consume written content through audio.

The project was originally inspired by frustration with traditional screen readers and text-to-speech tools that:

* sound robotic
* interrupt reading flow with citations and metadata
* read image captions and URLs aloud
* struggle with multi-column layouts
* provide little control over listening cleanup

This application attempts to create a cleaner and more human listening experience.

---

## Features

### Content Input

Supports:

* webpages
* PDFs
* Word documents (.docx)
* pasted text
* plain text files

### Listening Cleanup

Optional cleanup features include:

* remove citations
* remove references and bibliography sections
* remove URLs
* remove captions and metadata
* skip titles and publication dates
* skip author information
* start reading from a selected phrase

### Natural Voice Playback

Uses neural voices through Edge TTS.

Includes:

* pause
* replay
* rewind
* seek controls
* multiple natural voice selections

### Accessibility-Oriented Design

The project focuses on reducing listening friction rather than simply converting text to speech.

---

## AAEL Framework Connection

This project was developed using the AAEL framework:

### AI-Augmented Exploratory Learning

AAEL emphasizes iterative learning through:

1. Ask
2. Adapt
3. Analyze

This prototype was built through rapid human-AI collaboration involving:

* requirement refinement
* iterative debugging
* accessibility-focused problem solving
* rapid prototyping
* workflow adaptation

Development time from concept to functioning prototype was approximately 29 minutes.

---

## Tech Stack

* Python
* Streamlit
* Edge TTS
* BeautifulSoup
* PyMuPDF
* readability-lxml
* python-docx

---

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/human-reader-mvp.git
cd human-reader-mvp
```

Install requirements:

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install streamlit beautifulsoup4 requests pymupdf python-docx readability-lxml edge-tts pyttsx3
```

---

## Running the Application

Recommended:

```bash
python -m streamlit run human_reader_mvp.py
```

The application will open in your browser.

Default local URL:

```text
http://localhost:8501
```

---

## Example Workflow

1. Paste a webpage URL or upload a document
2. Extract text
3. Apply cleanup options
4. Select a natural voice
5. Generate audio
6. Listen through browser playback controls

---

## Future Development Ideas

Potential future enhancements include:

* OCR for scanned PDFs
* semantic paragraph cleanup using LLMs
* adaptive pacing for neurodivergent users
* audiobook-style narration modes
* summarization before playback
* user profiles and listening presets
* deployment through Streamlit Cloud
* chunked streaming audio generation
* citation suppression scoring
* layout reconstruction for complex academic papers

---

## Research Context

This project is connected to ongoing doctoral research in:

* AI-Augmented Exploratory Learning (AAEL)
* Cognitive Apprenticeship
* Human-AI collaboration
* Accessibility and assistive technology
* Professional learning with AI

---

## Author

Robert Foreman
Doctoral Candidate - DET
Central Michigan University

Research Focus:

* AI-Augmented Exploratory Learning (AAEL)
* Cognitive Apprenticeship
* How Professionals Learn with AI

Website: [https://www.nhancedata.com](https://www.nhancedata.com)
Email: [forem1r@cmich.edu](mailto:forem1r@cmich.edu)
Mobile: 480-415-0783

---

## License

MIT License

