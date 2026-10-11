LangChain Learning
This repository contains my journey learning AI Engineering and LangChain.

Lesson 1 - First Chat Model
Technologies Used
Python
LangChain
Ollama
Qwen2.5:3b
Code
from langchain_ollama import ChatOllama

llm = ChatOllama(model="qwen2.5:3b")

response = llm.invoke(
    "What is AI?"
)

print(response.content)