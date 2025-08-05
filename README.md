# GPT-4o Vision – Email Banner Generator

This project uses OpenAI's GPT-4o Vision (Image 1) API to generate **email banners** based purely on the email body content.

It supports prompt tuning (style, tone, background) and saves base64-generated images locally — no design tools needed.

---

## 🚀 Features

- Generate banners directly from structured prompts
- Customize by style, tone, and background
- Supports Email, WhatsApp, and SMS visual formats
- Saves images locally and logs prompt metadata
- Fully base64 → image pipeline using OpenAI API

---

## 📁 Folder Structure
├── generate_banners.ipynb # Main notebook
├── requirements.txt # Python dependencies
├── README.md # Project overview
├── generated_banners/ # Saved image outputs
└── .env # API keys and config 


1. Clone this repo  
2. Create a `.env` file with the following:

    ```env

    OPENAI_API_KEY=your-key
    OPENAI_API_BASE=https://your-endpoint
    DEPLOYMENT_NAME=your-deployment
    API_VERSION=2024-05-15-preview

    ```

3. Install requirements:
   pip install -r requirements.txt


4. Run the notebook
