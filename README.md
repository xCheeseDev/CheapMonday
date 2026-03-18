# CheapMonday
desktop robot that interacts with your smart home system and talks to you, no cloud all local hosted connecting to a local server to run

## AI Chat Feature
This project includes an AI chat feature using Google's Gemini API for conversational interactions.

### Setup
1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Get a Google AI API key from [Google AI Studio](https://makersuite.google.com/app/apikey).

3. Set the API key as an environment variable:
   ```
   export GOOGLE_API_KEY=your_api_key_here
   ```

4. Run the chat script:
   ```
   python main.py
   ```

### Usage
- Start a conversation with the AI.
- Type 'quit' to exit.

Note: This feature uses Google's cloud API, which may contradict the "no cloud" principle. Consider using a local LLM for fully local operation.
