# LLM RAG Test
An exercise to test RAG (Retrieval-Augmented Generation) feature with LangChain. It is a project that is based on all my previous work of a developer.

## Description

This project has the goal to practise the learning of RAG process with in LLM using LangChain.

The project aggregates a developer's Curriculum Vitae, personal projects with descriptions, and client projects with relevant details such as timelines. All data is organized in a JSON file containing paths to these resources, which may be in markdown or PDF format. This information is then transformed into a vector database for use with LangChain in RAG workflows.

There are three main features:
- A chat assistant where users can inquire about the developer or projects they have contributed to.
- An entertaining chatbot mode where the AI humorously comments on the developer's experience and work history, using emojis and witty remarks.
- A proposal generator that creates tailored proposal texts based on client requirements.

## Environment Setup

## Conda Environment
Create a conda environment using the provided environment.yml file:
```bash
conda env create -f environment.yml
conda activate llm-rag-test
```

### OpenAI API Key
You need to add your OpenAI API key in a .env file in the root of the project:
```
OPENAI_API_KEY=your_openai_api_key
```