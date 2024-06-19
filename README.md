# Code Runner API

This Flask application allows users to run code snippets written in Python, Java, JavaScript, and TypeScript. It exposes a single endpoint `/run` that accepts POST requests with the code and language specified, executes the code, and returns the output or error messages.

## Features

- Execute Python, Java, JavaScript, and TypeScript code.
- Supports CORS for the specified frontend domain.
- Returns output and error messages from the code execution.

## Requirements

- Python 3.x
- Flask
- Flask-CORS