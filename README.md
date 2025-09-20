AI-Based Fraud Detection in NBFC / Banking Using Conversational Agents

Project Overview:
  This project demonstrates a Generative AI-powered conversational agent that helps NBFCs and banks detect potential fraud or high default risk in loan applicants. The AI analyzes conversations, documents, and applicant behavior to identify inconsistencies, assign risk scores, and recommend verification or escalation steps.

Features:

  Conversation Analysis
  
  Processes chat transcripts, voice-to-text conversations, emails, and form submissions.
  
  Detects suspicious patterns, evasive answers, or conflicting information.
  
  Document Verification
  
  Analyzes uploaded IDs, income proofs, bank statements, and invoices.
  
  Flags inconsistencies or anomalies for further verification.

Risk Assessment & Alerts:

  Generates a risk score (Low / Medium / High) for each applicant.
  
  Suggests actions like additional verification or manual escalation.

Interactive Coaching / Guidance:

  Engages with applicants politely to clarify suspicious details.
  
  Maintains regulatory-compliant, non-accusatory communication.

Output Structure:

  Applicant Risk Score: Low / Medium / High
  
  Suspicious Findings: Key inconsistencies or anomalies
  
  Suggested Actions: Verification, escalation, or approval with caution

Technologies Used:

  Generative AI / LLM: For conversational analysis and risk detection
  
  Python / Node.js / JavaScript: Backend for processing data
  
  Speech-to-Text API: To transcribe voice calls
  
  Document Analysis Tools: For verifying IDs and income proofs
  
  JSON / CSV: For storing conversation logs and applicant data

Sample Conversation:
  Applicant: I earn around ₹80,000 per month.
  AI Agent: Thank you. What is your current employment status?
  Applicant: I am self-employed.
  AI Agent: Please upload your last 3 months of bank statements.
  Applicant: Sure. (uploads statements showing ₹25,000 average deposits)
  AI Agent: Reported income is ₹80,000 but bank deposits show ₹25,000. Please clarify.
  Applicant: I receive some payments in cash.
  AI Agent: Thank you. Recommend submitting tax returns or invoices for verification.

How It Works:

  Input: Applicant provides income, expenses, goals, documents, and chats with the AI agent.
  
  Processing: AI analyzes conversation patterns, document consistency, and behavioral signals.
  
  Output: Risk score, suspicious findings, and suggested actions.

Demo / Prototype:

  Upload applicant conversation logs (JSON/CSV) and documents.
  
  AI generates real-time risk assessment.
  
  Interactive dashboard shows flagged inconsistencies and escalation recommendations.

Future Enhancements:

  Integrate real-time voice call monitoring.
  
  Add machine learning models for historical fraud pattern detection.
  
  Include dashboard visualization of high-risk applicants.
  
  Multilingual support for regional loan applicants.

Authors:

  Karanam Swathi – Fullstack Developer
