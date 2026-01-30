# Rule-Based Alien Chatbot 🛸

A Python-based chatbot that uses Regular Expressions (Regex) to simulate a conversation with an alien visitor. This project demonstrates how rule-based logic can handle user intents and provide automated responses.

## Features
- Intent Matching: Uses the re module to identify what the user is asking.
- Conversation Flow: Greets the user, asks random alien questions, and handles exit commands.
- Dynamic Responses: Selects random replies from a set of predefined rules to keep the chat interesting.

## How to Use
1. Make sure you have Python installed.
2. Download or clone the repository.
3. Run the script in your terminal or a Jupyter/Colab notebook.

## Project Structure
- RuleBot Class: The main engine of the chatbot.
- alienbabble: A dictionary containing Regex patterns for different intents.
- Intent Methods: Functions like describe_planet_intent and answer_why_intent that return specific responses.

## Example Exit Commands
You can stop the chat by typing:
- quit
- exit
- goodbye
- bye

## Built With
- Python
- Regular Expressions (re)
- Random module