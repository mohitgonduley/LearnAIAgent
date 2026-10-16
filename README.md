# LearnAIAgent
LearnAIAgent


source ./.venv/bin/activate
./.venv/bin/python3 -m pip install --upgrade pip # if pip is not installed
pip install google-genai python-dotenv #install Google Gen AI Python SDK to communicate directly with Google's Gemini models.


Set following environmental variables in .env file which you received from "https://openrouter.ai/"

BASE_URL="https://openrouter.ai/api/v1"
API_KEY=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
MODEL=google/gemini-2.5-flash

Run the python code
python hello_ai.py

