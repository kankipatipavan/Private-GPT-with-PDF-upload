# Chat-with-PDF-Chatbot
This Chatbot is an interactive app developed to assist users to interact with their PDF. It is built using Open Source Stack. No OpenAI is required.

## Getting Started

Follow these steps to set up and run the project on your local machine.


### Installation

```sh
## Clone the repository
git clone <repository_url>

## Create the necessary folders
mkdir db
mkdir models
## Add your model files downloaded from the hugging face page to the 'models' folder

Please download the model or clone the model from the hugging face web page. and use it in the model folder.

mkdir docs

### Run the Requirements.txt

'pip install -r requirements.txt'

----
### Usage 

## Run the ingestion script to prepare the data

`python ingest.py`

## Start the chatbot application using Streamlit

`streamlit run chatbot_app.py`


#model folder should be created with the model 
from te git clone https://huggingface.co/MBZUAI/LaMini-T5-738M


#Links:
https://github.com/AI-Yash/st-chat/tree/main?tab=readme-ov-file
https://github.com/AIAnytime/Chat-with-PDF-Chatbot
