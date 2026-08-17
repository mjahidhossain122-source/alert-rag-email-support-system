alert-rag-email-system
<br>
Author: MD.Jahid Hosen
<br>
# alert-rag-email-support-system- short explanation:
RAG email system that reads, understands, and categorizes emails into General, Urgent, and Booking. It checks calendar availability before booking meetings, reduces token usage, and sends Telegram alerts 30 minutes before meetings plus a daily morning meeting summary.
This system automatically manages incoming emails from start to finish.

1. Email Reading
   The system reads the email subject and body and understands the user’s request.

2. Email Categorization
   Each email is classified into three categories:

* General
* Urgent
* Booking

3. RAG-Based Response
   The RAG system searches the knowledge base for relevant information before generating a reply. This reduces token usage and helps avoid incorrect AI guesses.

4. Meeting Booking
   For booking requests, the system first checks Google Calendar for available slots. It only books a meeting when a suitable slot is free.

5. Human Control
   The booking process keeps a single human touchpoint for approval and control.

6. Telegram Alerts
   The system sends a Telegram alert 30 minutes before every scheduled meeting.

7. Daily Meeting Summary
   Every morning, the system sends the day’s complete Google Calendar meeting list through Telegram.

Workflow:
Incoming Email → Understand → Categorize → RAG Search → Generate Reply → Calendar Check → Book Meeting → Telegram Alert
