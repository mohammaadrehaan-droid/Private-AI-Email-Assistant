
# Private AI Email Assistant

## Overview

Private AI Email Assistant is an AI-powered email automation project built using **n8n, Gmail, and Llama Chat Model**.

The system automatically monitors incoming emails, extracts and cleans email content, analyzes messages using an AI Agent, and generates intelligent replies that are automatically sent to the original sender through Gmail.

The main goal of this project is to reduce manual email handling and demonstrate the practical use of AI Agents in real-world automation.

## Workflow Architecture

The automation consists of the following steps:

1. **Gmail Trigger:** Detects incoming emails automatically.
2. **HTML Data Extraction:** Extracts email content from HTML and cleans it into readable text.
3. **AI Agent:** Receives the cleaned email content and analyzes the sender's message using a custom prompt.
4. **Llama Chat Model:** Powers the AI Agent and generates an appropriate response.
5. **Send Email:** Sends the AI-generated reply through Gmail to the original email sender.

## Key Features

- Automatic incoming email detection.
- HTML email content extraction and cleaning.
- AI-powered email understanding.
- Custom prompt-based response generation.
- Llama Chat Model integration.
- Automatic email reply delivery through Gmail.
- Reduced manual email communication.

## Technologies Used

- **n8n:** Workflow automation platform.
- **Gmail Trigger:** Incoming email detection.
- **HTML Extraction:** Email content processing.
- **AI Agent:** Email analysis and response generation.
- **Llama Chat Model:** AI language model.
- **Gmail:** Automated email delivery.
- **JSON:** Workflow export and configuration.

## Workflow Structure

```text
Gmail Trigger
      |
      v
HTML Data Extraction
      |
      v
AI Agent
      |
      v
Llama Chat Model
      |
      v
Send Email (Gmail)
      |
      v
Automatic Reply Sent
```

## Installation & Setup

1. Install or open n8n.
2. Download the `workflow.json` file from this repository.
3. Import the workflow into your n8n workspace.
4. Connect your own Gmail account.
5. Configure your Llama Chat Model credentials and connection.
6. Review the AI Agent prompt and customize it according to your requirements.
7. Test the workflow with an incoming email.
8. Activate the workflow to enable automatic email replies.

## Security

- No private credentials or API keys are included.
- Users must configure their own Gmail and AI model credentials.
- Sensitive account information should not be shared publicly.

## Learning Objectives

This project demonstrates practical experience with:

- AI Agent development.
- LLM integration.
- Prompt engineering.
- Gmail automation.
- HTML data extraction.
- Workflow design using n8n.
- Real-world AI automation applications.

## Author

AI Automation & ML Engineering Learner
