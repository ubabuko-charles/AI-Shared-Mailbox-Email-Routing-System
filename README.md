# AI-Powered Shared Mailbox Email Routing System

## Overview

An intelligent email automation solution built using Microsoft Power Automate, Microsoft 365, Outlook Shared Mailbox, and SharePoint Online.

The system automatically processes incoming emails, evaluates routing rules, forwards messages to the correct destination, and maintains an audit trail of processed emails.

This project demonstrates enterprise workflow automation, approval logic, SharePoint integration, and scalable Microsoft Power Platform development.

---

# Business Problem

Organizations receive large volumes of emails daily that require manual sorting and forwarding.

Manual email handling can lead to:

- Delayed responses
- Incorrect routing
- Poor visibility into email processing
- Increased administrative workload

---

# Solution

This project automates the email routing process using Microsoft Power Automate.

When an email arrives in a shared mailbox, the workflow:

1. Detects incoming emails.
2. Retrieves email details and attachments.
3. Applies classification logic.
4. Checks routing rules stored in SharePoint.
5. Automatically forwards emails.
6. Logs processing activities for tracking and auditing.

---

# Features

## Automated Email Processing

- Monitors Microsoft 365 shared mailbox.
- Processes incoming emails automatically.
- Handles email attachments.

## Dynamic Routing

- Uses SharePoint routing rules.
- Determines the correct destination department.
- Supports configurable forwarding logic.

## Audit Logging

Every processed email is recorded with:

- Sender information
- Department classification
- Processing status
- Timestamp
- Routing decision

## Microsoft 365 Integration

Built using:

- Power Automate
- Outlook Connector
- SharePoint Online

---

# Technology Stack

| Technology | Purpose |
|---|---|
| Microsoft Power Automate | Workflow automation |
| Microsoft 365 Outlook | Email processing |
| SharePoint Online | Data storage and routing rules |
| Power Platform | Low-code application development |

---

# Architecture
 ```text
      Incoming Email
            ↓
    Power Automate Flow
            ↓
     Email Processing
            ↓
 SharePoint Routing Rules
            ↓
      Forward Email
            ↓
      Audit Logging
```


---

# SharePoint Lists

## RoutingRules

Stores email routing configuration.

Example fields:

- Department
- Email Address
- Auto Forward

---

## EmailAuditLog

Stores workflow history.

Example fields:

- Email Subject
- Sender
- Department
- Action Taken
- Date Processed

---

# Workflow

1. Email arrives in shared mailbox.
2. Power Automate triggers.
3. Email information is extracted.
4. Routing rules are retrieved from SharePoint.
5. Workflow decides forwarding action.
6. Email is forwarded.
7. Processing details are logged.

---

# Screenshots

## Flow Design

![Flow](Screenshots/flow.png)

## Routing Rules

![Routing Rules](Screenshots/routing-rules.png)

## Audit Log

![Audit Log](Screenshots/audit-log.png)

---

# Future Enhancements

Planned improvements:

- Azure OpenAI integration for intelligent email classification.
- AI-powered document understanding.
- Confidence scoring.
- Advanced exception handling.
- Automated notifications.

---

# Learning Outcomes

This project demonstrates experience with:

- Microsoft Power Platform development
- Power Automate workflow design
- SharePoint integration
- Business process automation
- Enterprise email solutions

---

# Author

UBABUKO CHARLES IKECHUKWU

Power Platform Developer | Microsoft 365 Automation
