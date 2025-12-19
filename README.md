# n8n-multi-persona-ai-chatbot
An n8n-based multi-persona AI chatbot powered by Google Gemini, enabling customizable conversational agents through automated workflows.

## Overview
This project provides an AI chatbot workflow built in **n8n** that supports multiple personas using **Google Gemini**. It can be integrated into websites, apps, or any system that can send HTTP requests.

## Setup Instructions

### 1. Install & Run n8n
Install n8n locally or via Docker and start the n8n editor.

### 2. Import the Workflow
- Create a new workflow in n8n
- Import the provided **JSON workflow file**
- Save the workflow

### 3. Configure Credentials
- Add your **Google Gemini API credentials** in n8n  
- You can either:
  - Update credentials directly in the nodes, or
  - Edit them inside the JSON file before importing

### 4. Test the Chatbot
- Trigger the workflow using **Postman** (HTTP request)
- Verify the AI response based on the selected persona

### 5. Use in Your Application
After testing, you can use this workflow anywhere you need AI assistance (websites, apps, backend services, etc.).

A **simple HTML test file** is also included, demonstrating how the chatbot was used.
⚠️ Make sure to update the API route in the script with your actual n8n webhook URL.

## License
This project is open for use and modification, but ownership rights remain with the original author.

