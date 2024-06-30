# MeWell Chatbot for Mental Well-being using RAG 
### Prepared under the guidance of Hackathon Raptors Mentor

MeWell Chatbot is a powerful tool designed to provide mental support to the user by understanding user queries using state-of-the-art language models and vector stores.

 ## Tech Stack used:

 - Python 3.11
 - Mistral7B Open Source Model
 - Huggingface
 - Haystack
 - Chainlit
 - Transformer

### Installation

- Clone this repository to your local machine.


'git clone https://github.com/pawan-kumar-108/MeWell_MentalWellness.git'
'cd MentalHack'


- Create a Python virtual environment (optional but recommended):

''' python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
'''

- Install the required Python packages:

'pip install -r requirements.txt'

- Access the HuggingFace access token and take permission to use it through huggingface.com



### Getting Started

To get started with the MeWell Chatbot, you need to:

- Set up your environment and install the required packages as described in the Installation section.

- Put the KnowledgeBase1 file and KnowledgeBase2 into document_ (as specified in the code).
  (You may modify it as per your requirements)

- Configure your project by updating the InMemoryDocument variable and any other custom configurations in the code.

- Prepare the language model and data as per the HF documentation.

- Start the bot by running the provided Python script or integrating it into your application.

 ## Start the chatbot application using Chainlit

`chainlit run final.py -w`


### Usage
The  Chatbot can be used for answering mental health related queries. To use the bot, you can follow these steps:

Start the bot by running your application or using the provided Python script.

Send a mental health related query to the bot.

The bot will provide a response based on the information available in its database.

If sources are found, they will be provided alongside the answer.

The bot is customized to return specific information based on the query and context provided.

###

For any queries, reach out to pawangugm@gmail.com (Team TechBeetles (MeWell) )

