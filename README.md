# AI Automation Projects | n8n & LLMs

A portfolio of practical AI automation projects built with **n8n, Large Language Models (LLMs), APIs, and workflow automation**. These projects demonstrate how AI can be integrated into real-world business processes to improve efficiency, automate repetitive tasks, enhance customer communication, and support decision-making.

## Projects Overview

| # | Project | Description |
|---|---|---|
| 1 | AI Lead Intake & Qualification | Captures, classifies, and qualifies incoming leads. |
| 2 | AI Email Drafting | Generates contextual email drafts using AI. |
| 3 | Human Approval & Email Automation | Adds human review before sending AI-generated emails. |
| 4 | AI Chatbot with Content Guardrails | Restricts chatbot responses to approved topics and rules. |
| 5 | Customer Support Chatbot with RAG | Retrieves relevant knowledge base information to answer customer questions. |
| 6 | Image Difference Detector Agent | Identifies and analyzes differences between images. |

---

## 1. AI Lead Intake & Qualification

**Objective:** Automate the initial stages of lead management, from receiving inquiries to assessing lead quality.

### Workflow
1. Receive incoming lead information through a webhook.
2. Extract and organize the submitted information.
3. Use an LLM to classify the inquiry and assess lead qualification.
4. Route leads according to their qualification status.
5. Store relevant lead information in a connected data source or CRM.

### Key Features
- Automated lead intake.
- AI-powered inquiry classification.
- Qualified, potential, and unqualified lead routing.
- Structured output for downstream automation.
- Integration-ready workflow architecture.

**Business application:** Helps sales teams reduce manual lead processing and prioritize promising opportunities.

## 2. AI Email Drafting Workflow

**Objective:** Generate relevant email drafts automatically based on incoming messages and their context.

### Workflow
1. Receive or retrieve an incoming email.
2. Extract the email content and relevant context.
3. Use an LLM to understand the message and draft an appropriate response.
4. Return the generated draft for review or further processing.

### Key Features
- Context-aware email generation.
- Automated response preparation.
- Structured AI outputs.
- Reduced repetitive writing.
- Support for customer inquiries and business communication.

**Business application:** Helps teams prepare consistent responses faster while retaining control over outgoing communication.

## 3. Human Approval & Email Automation

**Objective:** Introduce a human-in-the-loop approval process before an AI-generated email is sent.

This project extends the email drafting process into a controlled communication workflow.

### Workflow
1. Receive the AI-generated email draft.
2. Present the draft for human review.
3. Allow the reviewer to approve or reject the proposed response.
4. Send the email only after approval.
5. Handle the approval outcome through the appropriate workflow path.

### Key Features
- Human oversight of AI-generated content.
- Approval-based execution.
- Separation of drafting and sending stages.
- Reduced risk of unintended communication.
- A foundation for auditable business automation.

**Business application:** Useful for sales outreach, customer support, internal communications, and other workflows where human authorization is required.

## 4. AI Chatbot with Content Guard
