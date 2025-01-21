# RAG-based Conversational Bartender Chatbot

This project implements a Retrieval-Augmented Generation (RAG) conversational chatbot designed to provide cocktail recommendations and recipes based on user input. The bot is equipped with memory to maintain context throughout a conversation, making interactions seamless and dynamic.

## Features
- **Cocktail Recommendations**: Suggests cocktails based on user preferences.
- **Recipe Generation**: Provides detailed recipes for requested cocktails.
- **Contextual Memory**: Maintains conversation history for context-aware responses.
- **RAG Architecture**: Combines retrieval-based and generative AI techniques for accurate and dynamic responses.

## Technology Stack
- **Programming Language**: Python
- **Frameworks & Libraries**:
  - [Gradio](https://gradio.app): For building the interactive user interface.
  - [LangChain](https://langchain.com): For implementing RAG-based logic and conversational memory.
  - [OpenAI API](https://openai.com/api/): For generative language model capabilities.
  - [Transformers](https://huggingface.co/transformers/): For embedding generation and text processing.
- **Storage**:
  - [FAISS](https://faiss.ai): For vector storage and similarity search.

## Setup Instructions

### Prerequisites
- Python 3.8 or higher
- An OpenAI API key
- Basic understanding of Python and AI concepts

### Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set your OpenAI API key as an environment variable:
   ```bash
   export OPENAI_API_KEY="your_openai_api_key"
   ```

### Running the Application
1. Launch the Gradio interface:
   ```bash
   python app.py
   ```
2. Open the provided local or public URL in your browser.
3. Start chatting with the bot by entering your queries.

## Usage
- **Ask for recommendations**:
  - Example: "What are some cocktails containing rum?"
- **Request recipes**:
  - Example: "Can you give me the recipe for a Mojito?"
- **Explore variations**:
  - Example: "What cocktails can I make with vodka and lemon?"

## File Structure
```
.
├── app.py                  # Main application script
├── requirements.txt        # List of dependencies
├── data/                   # Directory for storing any required data files
├── models/                 # Pre-trained and fine-tuned models (if applicable)
└── README.md               # Project documentation
```

## Future Enhancements
- Add support for multi-language interactions.
- Integrate more data sources for cocktail recipes.
- Enhance memory capabilities for long-term user preferences.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- OpenAI for providing GPT-based capabilities.
- Hugging Face for their robust NLP tools.
- LangChain for seamless RAG and memory integration.

---
