## LLMs on Custom Data using Langchain and RAGs!

In this project, I've implemented LLMs on custom data, using the power of Langchain and RAG.

## Getting Started

Add you openai api ket in **constants.py** file
You need to add supported files to docs folder, then execute the **index.py** to get those files indexed in vector database.

You do not need to reupload data again and again, you can just add more data to docs and execute **index.py** to index more and more data.

Then you can execute the **main.py** and you are good to go.

### 1-Cloning the Repository

To get started, you can clone this repository to your local machine using the following command:

```bash
git clone https://github.com/javaidiqba11/custom-rags-llm-langchain.git
```

### 2- Install Required Libraries
To install the requirements, run the command.

```bash
pip install -r requirements.txt
```

### 3- Indexing
Create a folder named docs, add supported files given below to docs.

```text
Supported Document Types:

PDF (.pdf)
Text (.txt)
Word (.docx)
Excel (.xlsx)
PowerPoint (.pptx)
HTML (.html)
Markdown (.md)
EPUB (.epub)
Image (.jpg, .jpeg, .png)
CSV (.csv)
JSON (.json)
XML (.xml)
```
Run the command:

```bash
python index.py
```

### 4- Retrieval and Generating 
To start the ChatBot, run the command
```bash
python main.py
```

### 5- Running ChatBot
Running the ChatBot using the above commands. 


### Note:
Feel free to explore the code, open issues, and make pull requests. I appreciate your support and look forward to collaborating with you!
