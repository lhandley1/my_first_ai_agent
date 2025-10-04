# My First AI Code Agent with Smolagents 🤖

## Overview

This project is my first introduction to the world of AI agents, specifically focusing on building a code agent using the smolagents framework. So far, I have installed the necessary libraries, set up access to the Hugging Face API, created a `CodeAgent` with a specific language model, and attempted to implement and use a custom tool. The initial goal is to create a basic agent that can utilise custom tools to perform specific tasks, starting with a simple tool to get the current time. This project is a learning experience to build a foundational understanding before exploring more advanced agent capabilities.

## Smolagents Framework 🤖

[Smolagents](https://github.com/smol-ai/smolagents) is a lightweight framework for building AI agents that focus on code generation.

## How to Run

1.  **Open in Google Colab:** Click the "Open In Colab" badge above or upload and open the notebook in Google Colab.
2.  **Install Dependencies:** Run the cell containing `pip install 'smolagents[toolkit]'` to install the required libraries.
3.  **Set up Hugging Face API Token:**
    *   Obtain a Hugging Face API token with permissions for Inference Providers.
    *   In Google Colab, go to the "🔑" icon (Secrets) in the left sidebar.
    *   Add a new secret with the name `HF_TOKEN` and paste your Hugging Face token as the value.
    *   Run the cell that retrieves the `HF_TOKEN` from userdata.
4.  **Create the Code Agent:** Run the cell that defines and initializes the `CodeAgent` with the chosen model.
5.  **Define Custom Tool:** Run the cell that defines the `get_current_time` custom tool.
6.  **Run the Task:** Execute the cell that calls `agent.run()` with the task you want the agent to perform.
