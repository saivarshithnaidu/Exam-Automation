# Job Application Form

This is start-up template for a simple Job Application Form built with HTML and CSS. It allows users to submit their application details including Name, Email, Phone Number, and a Resume file.

## Features

- **Responsive Design**: Clean and simple UI.
- **Form Fields**:
    - Full Name
    - Email Address
    - Phone Number
    - Resume Upload (PDF, DOC, DOCX support)
- **Integration Ready**: Designed to work with an n8n webhook or any backend endpoint.

## Setup Instructions

1.  **Clone or Download**: Get the `resume_upload.html` file.
2.  **Configure Webhook**:
    Open `resume_upload.html` in a text editor and locate the `<form>` tag:
    ```html
    <form action="PASTE_YOUR_N8N_WEBHOOK_URL_HERE" method="POST" enctype="multipart/form-data">
    ```
    Replace `PASTE_YOUR_N8N_WEBHOOK_URL_HERE` with your actual n8n webhook URL or backend endpoint.

## Usage

1.  Open `resume_upload.html` in your web browser.
2.  Fill in the required details.
3.  Upload your resume.
4.  Click "Submit Application".

## Technologies Used

- HTML5
- CSS3
