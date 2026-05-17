# lead-qualification-chatbot-n8n
AI-powered ecommerce assistant and lead qualification workflow built with n8n and OpenAI.

# n8n Ecommerce AI Agent

AI-powered ecommerce workflow built with n8n and OpenAI.

This project includes two AI workflows:

- Lead Qualification Agent
- Ecommerce Support Chatbot

## Features

### Lead Qualification
The workflow analyzes customer conversations and determines whether the customer is a good bulk-order lead.

The AI checks for:
- Bulk quantities
- Corporate/team orders
- Event merchandise
- Custom branding or logos
- Wholesale intent

Structured JSON output includes:
- Customer name
- Lead status
- Reasoning

---

### Ecommerce Chatbot
AI assistant capable of handling:

- Product questions
- Bulk pricing
- Shipping information
- Return policy
- Custom logo requests

Includes:
- Memory buffer for conversations
- Bulk discount logic
- Order intent detection

---

## Tech Stack

- n8n
- OpenAI GPT-4o-mini
- LangChain Nodes
- JSON Structured Output Parsing

---

## Bulk Discount Rules

| Quantity | Discount |
|---|---|
| 50+ | 10% |
| 100+ | 15% |
| 250+ | 20% |
| 500+ | 25% |

---

## Setup

### 1. Import Workflow
Import the workflow JSON file into n8n.

### 2. Configure OpenAI Credentials
Add your OpenAI API credentials inside n8n:

- Settings → Credentials
- Create OpenAI Credential

### 3. Run
Use:
- Manual trigger for testing
- Chat trigger for chatbot mode


---

## License

MIT
