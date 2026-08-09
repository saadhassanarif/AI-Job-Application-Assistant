AI Job Application Assistant

An end-to-end AI automation that helps job seekers turn a CV and job description into a personalised job application pack.

Overview
The workflow collects a user's details through Google Forms, sends the CV and job description to OpenAI through Zapier, creates a tailored Google Doc, changes the document permissions to view-only, and emails the result to the user.

Problem

Preparing a job application can take a significant amount of time. Applicants often need to:

Analyse the job description
Compare their experience with the role
Tailor CV bullet points
Write a cover letter
Prepare interview questions
Identify gaps before applying

This project automates much of that process while keeping the final output personalised.

Workflow

Google Form
    ↓
Zapier
    ↓
OpenAI
    ↓
Google Docs
    ↓
Google Drive sharing
    ↓
Gmail delivery

How It Works

1- The user submits a Google Form containing:
Full name
Email address
Target job title
Company name
CV text
Job description
Preferred tone

2- Zapier detects the new form response.
3- OpenAI analyses the CV against the job description.
4- The AI generates a personalised job application pack.
5- Zapier creates a new Google Doc using the AI-generated response.
6- Google Drive changes the document permission to Anyone with the link — Viewer.
7- Gmail sends the document link to the email address entered in the form.

Generated Output

The job application pack includes:

- Job Match Score
- Candidate strengths
- Potential gaps
- Key job requirements
- Tailored CV bullet points
- Personalised cover letter
- Likely interview questions
- Application improvement suggestions

Tech Stack

- Google Forms — collects user information
- Zapier — manages the automation
- OpenAI API — analyses the CV and generates the report
- Google Docs — creates the application pack
- Google Drive — manages sharing permissions
- Gmail — delivers the report

Screenshots

Add your screenshots to an Images folder, then replace the example paths below.

Automation Workflow



Input Form



Generated Application Pack



Email Delivery



Key Learning Outcomes

Through this project, I gained practical experience in:

Designing an end-to-end AI workflow
Mapping dynamic data between applications
Connecting an external API to Zapier
Writing and refining prompts for structured outputs
Debugging authentication and permission issues
Creating documents automatically
Configuring dynamic file sharing
Delivering results through automated email

Privacy and Security

This repository does not contain:
- API keys
- Google account credentials
- Personal CVs
- Private email addresses
- Live Zapier connection details

Any screenshots used in this repository should contain fictional or anonymised user information.

Current Status

The workflow is functional and can:

- Accept new form submissions
- Generate a personalised report
- Create a new Google Doc
- Make the document viewable through a link
- Email the correct document to the user

Future Improvements

Possible future improvements include:

- Accepting PDF or DOCX CV uploads
- Adding stronger document formatting and branding
- Converting the final report to PDF
- Adding an approval step before sending
- Storing submission data in a dashboard
- Adding usage limits and cost monitoring
- Replacing the Google Form with a dedicated web interface

Demo

A short demonstration video will be added here.

Disclaimer

The generated content should be reviewed by the applicant before use. The workflow is instructed not to invent qualifications, responsibilities, achievements, employers, dates, or experience.

Author

Saad Hassan

Interested in AI automation, AI consulting, workflow design, and practical applications of AI for business.
