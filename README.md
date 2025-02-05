---

# LLM Agents LangChain and OpenAI

---

This repository contains a Jupyter notebook demonstrating the use of LangChain and OpenAI agents for various tasks. The agents are designed to handle natural language processing tasks, including weather information retrieval, word count analysis, and more.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Examples](#examples)

## Introduction

This project showcases how to leverage LangChain and OpenAI agents to perform various tasks such as retrieving weather information and analyzing word counts in texts. The agents utilize tools like `open_weather_map` and `duckduckgo_search` to provide accurate and timely information.

## Installation

To use this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/LLM_Agents_LangChain_And_OpenAI.git
    cd LLM_Agents_LangChain_And_OpenAI
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Open the Jupyter notebook to explore and execute the provided code:

```bash
jupyter notebook LLM_Agents_LangChain_And_OpenAI.ipynb
```

Run the cells in the notebook to see the agents in action. The notebook includes examples of how to use the agents for different tasks.

## Features

- Retrieve weather information for specific locations using OpenWeatherMap API.
- Perform word count analysis using DuckDuckGo search.
- Demonstrate the integration of LangChain and OpenAI agents for natural language processing tasks.

## Examples

### Retrieve Weather Information

The agent retrieves the current weather information for Colombo, Sri Lanka, where the Lotus Tower is located:

```python
response = agent_executor.invoke({"input": "What is the temperature of Colombo, Sri Lanka?"})
print(response["output"])
```

### Word Count Analysis

The agent performs a word count analysis for a given text or topic:

```python
response = agent_executor.invoke({"input": "introduction to deep learning word count"})
print(response["output"])
```

---
