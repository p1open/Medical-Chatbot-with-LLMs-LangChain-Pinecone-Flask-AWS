# Medical-Chatbot-with-LLMs-LangChain-Pinecone-Flask-AWS

# How to run?
### STEPS:
Clone the repository

```bash
git clone https://github.com/p1open/Medical-Chatbot-with-LLMs-LangChain-Pinecone-Flask-AWS.git
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.10 -y
```

```bash
conda activate medibot
```

### STEP 02- Install the requirements

```bash
pip install -r requirements.txt
```

### Create a .env file in the root directory and add your Pinecone credentials as follows:
````bash
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

```bash
# run the following command to store embeddings to pinecone
python store_index.py
```

```bash
# Run the following command in one terminal first
ollama serve
``` 

```bash
# Finally run the following command in another terminal
python app.py
```

Now,
```bash
open up localhost:
```

# Techstack Used:
- Python
- LangChain
- Flask
- Ollama
- Pinecone