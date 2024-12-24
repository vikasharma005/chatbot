# Contextual Chatbot using NLP and TensorFlow

Welcome to the **Contextual Chatbot** project. This chatbot understands the context of user sentences and responds accordingly. The project leverages **Natural Language Processing (NLP)** and **TensorFlow** to build, train, and deploy a chatbot capable of intelligent conversations.

---

## Features
- **Contextual Understanding**: Processes conversational intents to respond accurately.
- **Deep Learning Model**: Uses a Neural Network built with TFlearn (a high-level API for TensorFlow).
- **NLP Integration**: Tokenization, stemming, and intent classification.
- **Persistence**: Saves and loads trained models using Pickle for efficient reuse.
- **Framework**: Framework for processing user inputs and delivering responses.
- **Interactive Interface**: Supports real-time conversation with users.

---

## Files Included
1. **`Contextual Chatbot - NLP and Tensorflow.ipynb`**: The Jupyter Notebook containing the step-by-step implementation of the chatbot.
2. **`Chatterbot.py`**: Python script to load the trained model and process user queries.
3. **`LICENSE`**: The license file for the project.
4. **`_config.yml`**: Configuration file for project settings.
5. **`chatbot.png`**: Visual representation of the chatbot workflow.
6. **`intents.json`**: JSON file containing conversational intents, patterns, and responses.

---

## Libraries Used
- **TFlearn**: High-level API for TensorFlow, designed to simplify deep learning experiments. [TFlearn Documentation](http://tflearn.org/)
- **TensorFlow**: Open-source platform for machine learning and deep learning. [TensorFlow Documentation](https://www.tensorflow.org/)
- **Natural Language Toolkit (NLTK)**: For tokenization, stemming, and preprocessing.
- **Pickle**: For saving and loading trained models.

---

## Getting Started

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/vikasharma005/chatbot.git
   cd chatbot
   ```
2. Install the required libraries:
   ```bash
   pip install tensorflow tflearn nltk
   ```

### Training the Chatbot
1. Open the Jupyter Notebook `Contextual Chatbot - NLP and Tensorflow.ipynb`.
2. Follow the steps to preprocess the `intents.json` file, train the model, and save it as a Pickle file.
3. The trained model will be saved for use in the `Chatterbot.py` script.

### Running the Chatbot
1. Execute the `Chatterbot.py` script:
   ```bash
   python Chatterbot.py
   ```
2. Enter your queries, and the chatbot will respond contextually.

---

## How It Works
1. **Data Preparation**:
   - The `intents.json` file contains predefined intents, patterns, and responses.
   - Text preprocessing includes tokenization and stemming to clean and standardize the data.

2. **Model Training**:
   - A Neural Network is built using TFlearn.
   - The model is trained on the processed intents to classify user queries into predefined categories.

3. **Response Framework**:
   - The trained model predicts the intent based on user input.
   - A response is selected from the intent's predefined replies in the `intents.json` file.

4. **Persistence**:
   - The trained model and data are saved as Pickle files.
   - These files are reloaded in `Chatterbot.py` for real-time conversations.

---

## Example Interaction
- **User**: "Hi there!"
- **Chatbot**: "Hello! How can I assist you today?"

- **User**: "What can you do?"
- **Chatbot**: "I can assist you with various tasks and answer your questions."

---

## Contributing
We welcome contributions to improve this project. Feel free to fork the repository and submit a pull request.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Authors
**Vikas Sharma** (GitHub: [vikasharma005](https://github.com/vikasharma005))

---

## Acknowledgments
Special thanks to the **FreeBirdsCrew** for their collaborative efforts on this project.

