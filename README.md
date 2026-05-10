## 📊 AI Review Sentiment Tracker
A simple automation that captures user reviews via a form, analyzes the "vibe" of the feedback using AI, and organizes everything into a Google Sheet.
## 🚀 How it Works

   1. User Input: The user enters their Name and a Product Review into an n8n Form (or similar trigger).
   2. AI Analysis: The text is sent to an AI Model (OpenAI), which determines if the review is "Good" or "Bad".
   3. Data Logging: The AI's verdict, along with the user's name and original review, is automatically saved as a new row in Google Sheets.

<img width="1440" height="900" alt="Screenshot 2026-05-10 at 11 57 28 PM" src="https://github.com/user-attachments/assets/7d76b12a-489d-458c-b567-436e0e98b33d" />

## 🛠️ Features

* Real-time Analysis: Get instant sentiment results as soon as the form is submitted.
* Simple Categorization: Cleans up messy feedback into clear "Good" or "Bad" labels for easy reporting.
* Cloud Storage: All data is safely stored in Google Sheets for further analysis or sharing.

## 📂 Tech Stack

* Automation: n8n
* Brain: OpenAI (GPT-4o or GPT-3.5)
* Database: Google Sheets

## ⚙️ Setup Instructions

   1. Google Sheet Setup: Create a sheet with three headers: Name, Review, and Sentiment.
   2. n8n Import: Import the provided .json workflow into your n8n instance.
   3. Connect Credentials:
   * Add your OpenAI API Key.
      * Connect your Google account (ensure your Redirect URIs match!).
   4. Activate: Turn the workflow on and share your form link!
