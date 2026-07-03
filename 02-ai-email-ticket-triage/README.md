# AI Email Ticket Triage

## Overview
This project automates email and ticket triage using AI to classify, prioritize, and route incoming messages to appropriate teams.

## Features
- Automated email classification
- Priority level assignment
- Intelligent routing to teams
- Spam/phishing detection
- Sentiment analysis

## Project Structure
```
02-ai-email-ticket-triage/
├── README.md
├── requirements.txt
├── src/
│   ├── email_triage.py
│   ├── classifier.py
│   └── router.py
├── data/
│   └── sample_emails/
└── output/
    └── triage_results/
```

## Getting Started
1. Install dependencies: `pip install -r requirements.txt`
2. Configure email/ticket API connections
3. Set up classification rules and routing policies
4. Run the triage process

## Technologies Used
- Python
- OpenAI API / LLM
- Email APIs (Gmail, Outlook, etc.)
- NLP for classification
- Queue management systems

## Classification Categories
- Support requests
- Sales inquiries
- Bug reports
- Feature requests
- Spam/Phishing
