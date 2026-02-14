

Overview

Code Summarizer is an automated email-driven system built with n8n that detects code snippets from incoming emails, analyzes them using language models, and responds with:

Clean, human-readable code summaries

Inline code explanations / comments

A structured task roadmap

The entire process runs without manual intervention — from email monitoring to response delivery.

Key Features

-Automated Email Monitoring
Continuously listens for incoming emails using IMAP.

-Code Detection Engine
Identifies code blocks inside email bodies.

-AI-Powered Code Summarization
Generates clear explanations and adds contextual comments.

-Task Roadmap Generation
Produces actionable next-step guidance based on the code.

-Automated Email Reply
Sends the final summary back to the original sender.

-Fully Automated Workflow
No manual processing required after setup.

System Architecture

-The workflow follows this pipeline:

-Email Trigger (IMAP) →

-Content Extraction →

-Code Detection Logic →

-LLM Processing (Summarization + Roadmap) →

-Response Formatter →

-Email Sender (SMTP)

Requirements

Before running the project, ensure you have:

n8n (local install or Docker)

Email account with IMAP enabled

API key for language model provider

(Optional) Python 3.9+ if using helper scripts
