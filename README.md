# 🇪🇺 European Energy Data AI Chatbot
This project is an AI-powered chatbot designed to provide real-time and forecast data on the European energy market. Users can ask questions in natural language about electricity load and generation forecasts for over 35 European countries, and the chatbot will retrieve and display the relevant statistics in a clean, user-friendly web interface.

**While the file itself is code, running it in a Jupyter environment will start the interactive chatbot application and make it accessible in your browser.**


## Key Features
1) Conversational AI: Programmed an AI Chatbot using the Google Gemini API to understand and respond to commodity-related queries in plain English.

2) Live Data Integration: Integrated the official ENTSO-E (European Network of Transmission System Operators for Electricity) API to retrieve and display real-time and forecast energy statistics.

3) Broad Coverage: The chatbot is capable of fetching precise, data-backed answers for 35+ European countries.

4) User-Friendly Interface: Implemented a simple and interactive web interface using the Gradio library for easy access and data visualization.

## How It Works
The chatbot follows a simple yet powerful workflow:

1) User Input: The user asks a question in the Gradio web interface (e.g., "What was the total load in Germany yesterday?").

2) AI Processing: The query is sent to the Google Gemini model, which uses advanced language understanding to parse the user's intent and extract key parameters like the desired data (load), country (Germany), and date (yesterday).

3) API Call: The structured information is used to make a precise call to the ENTSO-E API.

4) Data Display: The retrieved data is processed, summarized, and displayed back to the user in the Gradio interface as a summary and a detailed data table.
