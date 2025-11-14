# StarLife - Real-Time Voice Translation

A real-time simultaneous interpretation pipeline that translates English speech to multiple target languages using advanced AI services.

## Overview

This project provides a production-ready voice translation middleware that enables real-time, simultaneous interpretation with minimal latency. The system processes audio input, translates it, and outputs spoken translation in near real-time.

## Features

- **Simultaneous Interpretation**: Translation starts while you're still speaking
- **Interim Diffing**: Intelligently handles ASR interim results to avoid duplicate words
- **Context-Aware Translation**: Maintains conversation history for coherent translations
- **Low-Latency Streaming**: Audio plays as it's generated
- **Multi-Language Support**: Currently configured for Telugu, easily adaptable to other languages

## Technology Stack

- **Deepgram**: Speech-to-text (ASR) with medical model support
- **OpenAI GPT-4o**: Real-time translation with context awareness
- **ElevenLabs**: High-quality text-to-speech with low latency

## Quick Start

See the [detailed README](./real-time-voice-middleware/README.md) in the `real-time-voice-middleware` directory for setup instructions.

## Project Structure

```
starlife/
├── real-time-voice-middleware/
│   ├── pipeline.py          # Main translation pipeline
│   └── README.md            # Detailed documentation
└── README.md                # This file
```

## Current Configuration

- **Input Language**: English (US)
- **Output Language**: Telugu (configurable)
- **Voice**: Alisha (Indian female voice, optimized for Telugu)
- **Audio Format**: PCM 16kHz, 16-bit, mono

## License

This project is part of the StarLife platform.

