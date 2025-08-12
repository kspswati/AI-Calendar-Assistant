# AI Calendar Assistant

## Project Overview  
This project is an AI-powered calendar assistant built using **n8n**, **OpenAI’s Chat Model**, and **Google Calendar API**. It enables users to add events to their Google Calendar simply by sending natural language text commands. The workflow interprets user messages, extracts event details like date and time, and automatically schedules the event—saving time and simplifying calendar management.

## Features  
- **Natural language understanding:** Uses OpenAI’s chat model to parse text commands such as "Schedule a meeting tomorrow at 10 AM."  
- **Automated event creation:** Connects with Google Calendar to create events without manual entry.  
- **Dynamic context:** Provides current date and time information to the AI for accurate scheduling.  
- **Error handling:** Includes logging and troubleshooting steps to ensure smooth operation.

## Technologies Used  
- [n8n](https://n8n.io/) — Workflow automation platform  
- [OpenAI Chat Model](https://openai.com/api/) — AI model for natural language processing  
- [Google Calendar API](https://developers.google.com/calendar) — For managing calendar events

## Setup Instructions  
1. Sign up for n8n and create a new workflow.  
2. Add a chat trigger to receive event requests.  
3. Integrate the OpenAI chat model node to interpret commands.  
4. Connect Google Calendar node to create events.  
5. Add a system message with dynamic date info to give context to the AI.  
6. Test the workflow by sending chat messages and verify events in your calendar.

## How to Use  
- Send a message like: "Book a meeting with John tomorrow at 3 PM."  
- The AI agent parses your command and schedules the event automatically.  
- Check your Google Calendar to confirm the event was created.

## Troubleshooting  
- If events are scheduled at the wrong time, check the system message’s dynamic date setup.  
- Verify that the Google Calendar node receives the correct start and end times from the AI model.  
- Review workflow logs in n8n to debug communication between nodes.

## License  
This project is for personal use and learning purposes.
