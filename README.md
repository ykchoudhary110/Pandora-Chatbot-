AI Mental Health Chatbot (RAG-Based)

An AI-powered Mental Health Chatbot that provides empathetic, safe, and context-aware responses using a Retrieval-Augmented Generation (RAG) approach with semantic search.

🚀 Features
🧠 Understands user input using AI embeddings
🔍 Semantic similarity search using FAISS
💬 Provides relevant and empathetic responses
🚨 Detects crisis situations and gives safe guidance
📊 Works with large structured datasets (1000+ entries)
🎨 Clean and interactive UI using Gradio

⚙️ Tech Stack
Python
Pandas, NumPy
Sentence Transformers (Hugging Face)
FAISS (Vector Search Engine)
Gradio (UI Framework)

🧩 How It Works
User enters a query (e.g., “I feel stressed”)
Text is converted into numerical vectors (embeddings)
FAISS searches for similar prompts in dataset
Top matching results are retrieved
The most relevant solution is selected
Safety layer checks for crisis-related input
Final response is displayed to the user

📊 Dataset Structure

The chatbot uses a structured dataset with the following columns:

Prompt → User input examples
Intent → Type of query
Solution → Response to return
Severity → low / medium / high
Response Type → info / emotional / crisis
Keywords → important terms for matching

🚨 Safety Handling
Detects harmful phrases (e.g., self-harm, suicide)
Overrides normal response
Provides supportive and safe guidance
Encourages reaching out to trusted people or professionals

💻 Installation & Setup
1. Clone Repository
git clone https://github.com/your-username/ai-mental-health-chatbot.git
cd ai-mental-health-chatbot
2. Install Dependencies
pip install sentence-transformers faiss-cpu pandas gradio
3. Run the Project
python app.py

▶️ Usage
Enter your thoughts or problems in the input box
Click submit
Receive a supportive and relevant response

🎯 Objective
Provide accessible emotional support
Help users feel heard and understood
Offer quick guidance during stressful situations
Act as a support system (not a replacement for professionals)

📈 Future Improvements
Chat history (multi-turn conversation)
Voice input & emotion detection
Mobile app version
Multilingual support
Integration with professional counseling services

⚠️ Disclaimer

This chatbot is designed for support and guidance only.
It is not a substitute for professional medical or psychological help.

⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!



