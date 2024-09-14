# Medical Terminology Trainer

Medical Terminology Trainer is a Streamlit-based application designed to help medical students memorize and learn medical terms. It uses AI to generate quizzes and provide explanations across various medical specialties and learning modes.

## Features

- Interactive medical terminology quizzes
- Multiple learning modes (Flashcards, Multiple Choice, Fill in the Blank, etc.)
- Customizable medical specialties and difficulty levels
- AI-powered explanations and learning assistance
- Support for various AI models (OpenAI and Ollama)
- Session saving and loading functionality
- Token usage tracking
- Dark/Light theme options

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/lalomorales22/medical-terminology-trainer.git
   cd medical-terminology-trainer
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up your OpenAI API key:
   - Create a `.env` file in the project root
   - Add your OpenAI API key: `OPENAI_API_KEY=your_api_key_here`

## Usage

1. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

2. Open your web browser and go to `http://localhost:8501`

3.
3. Enter your name and configure your learning preferences in the sidebar:
   - Select a medical specialty
   - Choose a learning mode
   - Set the difficulty level
   - Specify the number of questions for quizzes

4. Click "Generate Quiz" to create a new set of questions based on your preferences

5. Answer the questions and receive immediate feedback

6. Use the chat interface to ask for explanations or additional information about medical terms

## Customization

- Modify the `MEDICAL_SPECIALTIES` and `LEARNING_MODES` lists in `app.py` to add or remove options
- Adjust the `custom_instructions` in the sidebar to change the AI's behavior and focus
- Add new quiz types or modify existing ones to suit different learning styles

## Features in Detail

### Quiz Modes
- **Flashcards**: Review terms and definitions
- **Multiple Choice**: Test your knowledge with options
- **Fill in the Blank**: Practice recall of specific terms
- **Matching**: Connect terms with their definitions
- **Etymology Exploration**: Learn the origins of medical terms
- **Clinical Scenarios**: Apply terminology in practical contexts
- **Visual Recognition**: Associate terms with medical imagery

### AI Assistant
The AI can provide detailed explanations, etymological breakdowns, and usage examples for medical terms. It adapts to your chosen difficulty level and learning mode.

### Progress Tracking
- Keep track of your quiz scores
- Save and load learning sessions to continue where you left off

### Customization
Tailor your learning experience by selecting specific medical specialties, difficulty levels, and preferred learning modes.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to all the medical students and professionals who provided feedback during the development of this tool.
- Special thanks to the open-source community for the libraries and frameworks used in this project.

## Support

If you encounter any issues or have questions, please file an issue on the GitHub repository.

Happy learning, future medical professionals!
