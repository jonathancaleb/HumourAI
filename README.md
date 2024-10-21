# HumourBot - AI-Powered Chatbot

**Language:** Python 3.11  
**Operating System:** Windows  

## Project Description

HumourBot is an AI-powered chatbot that leverages OpenAI's GPT model to generate witty, humorous responses. It is designed to engage users in light-hearted conversations, providing humor and entertainment. Whether you're looking for a joke, a funny comment, or a quirky interaction, HumourBot is here to keep things entertaining!

## Features

- **AI-Powered Chatbot:** Utilizes OpenAI's API to generate responses.
- **Humorous Interactions:** The chatbot's primary focus is humor.
- **Streamlit Integration:** Runs as a web app using Streamlit.
- **Customizable Prompts:** You can adjust the bot's behavior by fine-tuning its prompts.

## Requirements

Before you get started, you'll need to install the following Python packages:

```bash
pip install python-dotenv openai colorama streamlit
```

## Installation

1. Clone this repository or download the project files.

    ```bash
    git clone https://github.com/jonathancaleb/humourbot.git
    cd humourbot
    ```

2. Install the required Python packages:

    ```bash
    pip install python-dotenv openai colorama streamlit
    ```

3. Create a `.env` file in the project directory and add your OpenAI API key:

    ```
    OPENAI_API_KEY=your_openai_api_key
    ```

4. Run the Streamlit app:

    ```bash
    streamlit run main.py
    ```

5. Open your browser, and the chatbot interface should be available at `http://localhost:8501`.

## Usage

Once the app is running, you can interact with HumourBot by typing in questions or prompts, and the bot will respond with humorous replies using the GPT model from OpenAI. The interaction is geared towards generating witty and funny responses based on user input.

## Contributors

1. Caleb

## Course Credits

- **Course Link:** [OpenAI API for Python Developers](https://www.linkedin.com/learning/openai-api-for-python-developers)
- **Course Instructor:** [Sandy Ludosky](https://www.linkedin.com/learning/instructors/sandy-ludosky)

## Roadmap and Future Improvements

### 1. Personalization

- Allow users to personalize the bot by selecting a tone (e.g., sarcastic, goofy, dry humor, etc.).
- Add user profile integration so the bot can remember previous conversations and tailor responses accordingly.

### 2. Improved Error Handling

- Implement better error handling for API response timeouts or invalid input to provide a smoother user experience.
- Add fallback responses when the OpenAI API fails to generate a proper answer.

### 3. User Interaction Analytics

- Implement simple user interaction logging to analyze the most common prompts and responses.
- Use this data to improve humor generation based on user preferences.

### 4. UI/UX Enhancements

- Make the interface more visually engaging by adding custom styling and fun animations.
- Allow users to select themes or change backgrounds based on their preferences.

### 5. Multi-Language Support

- Add support for multiple languages so that the bot can interact with users worldwide.
- Use translation services like Google Translate to detect input language and generate responses accordingly.

### 6. Chat History

- Implement a feature where users can view chat history, export conversations, or even share them on social media.
- Add an option to save or clear chat history as needed.

### 7. Custom Humor Modules

- Add a feature where users can choose from different categories of humor, such as dad jokes, puns, dark humor, or meme references.
- Create humor 'modes' like quiz mode, trivia mode, or even a meme generator.

### 8. Voice Integration

- Integrate text-to-speech and speech-to-text features to allow users to talk to the bot rather than typing.
- Use voice-based humor delivery for a more interactive and engaging experience.

### 9. Integration with Other APIs

- Integrate with other APIs like Giphy or Tenor to include funny GIFs or memes in responses.
- Add social media integration, allowing the bot to fetch trending topics and make witty remarks about them.

### 10. AI Model Fine-Tuning

- Experiment with fine-tuning the GPT model on humor-specific datasets to make the bot’s responses even funnier.
- Explore different LLM models (e.g., GPT-4, Claude) for comparison in humor generation.
