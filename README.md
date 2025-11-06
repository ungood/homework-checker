# Canvas Homework Tool

A simple Python script for checking homework assignments using the
[Canvas API](https://developerdocs.instructure.com/services/canvas).

## Requirements

- Python 3.13+
- uv

## Setup

Set the following environment variables:

```bash
export CANVAS_URL="https://your-canvas-instance.com"
export CANVAS_API_KEY="your-canvas-api-key"
```

To get your Canvas API key:
1. Log in to your Canvas instance
2. Go to Account → Settings
3. Scroll down to "Approved Integrations"
4. Click "+ New Access Token"
5. Generate and copy your token

## Usage

Run the script:

```bash
./check-homework
```
