# PythonAIChatbot

- chatbot.py - Main application
- training.py - Training model
- intents.json - Training data

### requirements
- numpy
`pip install numpy`
- nltk (natural language toolkit)
`pip install nltk`
- tensorflow
`pip install tensorflow`

### Installation
1. Download the source code
2. Install required python packages
for example to install numpy, in command line type
`pip install numpy`

### Usage
1. First train the data, type following command, it will create a file called *chatbot_model.h5*
`python training.py`
2. Next to run the application in command line type the following line
`python chatbot.py`

### Notes
- Add your own training data to the intents.json
- Adding more training data make the chatbot works fine
- In intents.json file
    - **patterns** are the inputs to the chatbot (what you type in command line)
    - **responses** are the output from chatbot application
    - outputs are random. For example, if the input is *hi*, output can be any response from responses array.

