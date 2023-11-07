# OpenAI Assistants Template 🤖

## Introduction 🌟
Welcome to the OpenAI Assistants Template! This repository is a step-by-step tutorial 📚 for leveraging OpenAI's powerful Assistant API to build intelligent and conversational AI assistants. Whether you're a developer, a student, or just an AI enthusiast, this guide will help you harness the power of GPT models for your projects.

## Features 🚀
- Comprehensive guide on the Assistant API 🛠️.
- Interactive examples and use cases 📝.
- Modular code for quick learning and implementation 👩‍💻.
- Insights into best practices and advanced API features 🔍.

## Prerequisites ✅
To get the most out of this tutorial, you should have:
- Python knowledge (basic to intermediate) 🐍.
- An OpenAI API key 🔑.
- Python 3.6 or higher installed on your machine 💻.

## Setup and Installation 📈
1. Clone this repository to your local environment.
2. Rename `example.env` to `.env` and insert your OpenAI API key.
3. Run `pip install -r requirements.txt` to install dependencies.

## Usage 📖
Explore the `OpenAI-Assistant-Template.ipynb` for a hands-on experience that walks you through the capabilities of the Assistant API, enriched with practical examples.

## Modules Description 🧩
Dive into `modules.py` to find utility functions and classes that provide a cleaner and more maintainable codebase, making it easier to build upon.

## Utility Functions in `modules.py` 🧰
- `create_assistant(client, name, description, instructions, tools=[], model="")`: Create a new Assistant
- `get_assistant(client, assistant_id)`: Retrieve an existing assistant using an assistant ID.
- `start_new_chat(client)`: Start a new conversation with the AI assistant.
- `get_chat(client, thread_id)`: Retrieve an existing conversation using a thread ID.
- `add_message(client, thread, content)`: Send a new message to the Assistant within a conversation thread.
- `get_messages_in_chat(client, thread)`: Fetch all the previous messages within a conversation thread.
- `run_chat(client, thread, assistant)`: Process the conversation thread through the assistant for generating responses.

## Contributing 🤝
Your contributions make the open-source community an incredible arena for innovation. If you've got ideas on how to make this template even better, your pull requests are welcome! Let's make learning AI with OpenAI an exciting journey for everyone.

## License 📜
This project is open-sourced under the MIT License. Feel free to use it as you wish.

## Built With 💖 and:
- Python 🐍: The primary programming language used.