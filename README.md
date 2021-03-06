# Chatbot
## *A simple Retrieval Based Chatbot, using NLTK, Keras in python*

The is only aim of the project is to learn by creating a chatbot, retrieval based, using NLTK, Keras, etc

The chatbot will be trained on the dataset which contains categories (intents), pattern and responses.
We use a special recurrent neural network (LSTM) to classify which category the user’s message belongs to 
and then we will give a random response from the list of responses

---

### This project contains the following.
`Intents.json` – The data file which has predefined patterns and responses. <br>
`train_chatbot.py` – In this Python file, we wrote a script to build the model and train our chatbot. <br>
`Words.pkl` – This is a pickle file in which we store the words Python object that contains a list of our vocabulary.<br>
`Classes.pkl` – The classes pickle file contains the list of categories.<br>
`Chatbot_model.h5` – This is the trained model that contains information about the model and has weights of the neurons.<br>
`Chatapp.py` – This is the Python script in which we implemented GUI for our chatbot. Users can easily interact with the bot with this.<br>

### **Directions**:
1. Go ./main directory
2. Run `pip install -r requirements.txt`
3. Run `python train_chatbot.py`
4. Then Run `python chatapp.py` to start the chat server.
---
One of the main resource used in making this project was https://data-flair.training/blogs/python-chatbot-project/
