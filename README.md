
# Multi-Language Code Converter

A practical tool that converts code between Python, C++, and JavaScript using AI. Built this because I got tired of manually rewriting algorithms when switching between languages for different projects.

🔄Supported Conversions:

- Python ↔ C++

- Python ↔ JavaScript

- C++ ↔ JavaScript


## ✨Key Features

- Multi-directional conversion between Python, C++, and JavaScript
- AI-powered translation using DeepSeek's language model via OpenRouter API
- Interactive web interface built with Gradio for easy access
- Error recovery with retry mechanisms for improved conversion reliability


## ⚡ Language Support

- Python: Dynamic typing, list comprehensions, standard library functions
- C++: Modern C++17 features, STL containers, memory management
- JavaScript: ES6+ syntax, Node.js compatibility, async patterns


## 🚀Quick Start

Prerequisites

```bash
# Install compilers and runtime environments
sudo apt-get update && apt-get install -y nodejs npm g++

# Python dependencies
pip install openai gradio python-dotenv
```

Installation

```bash
git clone https://github.com/yourusername/multi-language-code-converter.git
cd multi-language-code-converter
pip install -r requirements.txt
```
Configuration

```bash
# Set your OpenRouter API key
OPENROUTER_API_KEY = "your-api-key-here"
```
Launch

```bash
python app.py
```

## Technical Stack

- Backend: Python 3.7+
- AI Model: DeepSeek Chat V3 via OpenRouter API
- Frontend: Gradio Web Interface
- Compilers: GCC (C++), Node.js (JavaScript)
## Demo

Insert gif or link to demo

