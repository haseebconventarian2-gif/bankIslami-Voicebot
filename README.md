<div align="center">

# BankIslami Voice Bot

FastAPI voice assistant using Azure OpenAI for text generation, speech-to-text, text-to-speech, and WhatsApp integration.

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Reference%20Implementation-6366F1)

</div>

---

## Overview

FastAPI voice assistant using Azure OpenAI for text generation, speech-to-text, text-to-speech, and WhatsApp integration.

## Highlights

- Text conversation endpoint
- Speech-to-text and text-to-speech
- Conversational AI responses
- WhatsApp and ACS integration

## Tech Stack

Python · FastAPI · Azure OpenAI · LangChain · FAISS

## Getting Started

```bash
git clone https://github.com/haseebconventarian2-gif/bankIslami-Voicebot.git
cd bankIslami-Voicebot
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
```

## Configuration

Configure Azure OpenAI deployments and any messaging-channel credentials in `.env`.

> Store credentials in `.env` and never commit secrets.

## Run

```bash
uvicorn main:app --host 0.0.0.0 --port 8000
```

## Project Status

This is a learning and reference implementation. Review security, validation, monitoring, and deployment settings before production use.
