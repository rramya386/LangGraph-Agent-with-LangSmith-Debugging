
# 🧠 LangGraph Agent with LangSmith Debugging

This project demonstrates how to build a simple LLM agent using [LangGraph](https://github.com/langchain-ai/langgraph), enhanced with LangSmith debugging capabilities. It integrates OpenAI's Chat Model and tools using LangChain and provides both a basic and tool-augmented agent workflow.

## 📦 Features

- ✅ LLM-powered agent workflow using LangGraph
- 🛠️ Tool-using agent with LangChain `@tool` decorators
- 🔍 Debugging enabled with LangSmith traces
- 🔐 Environment-secured API keys via `.env`

## 🚀 How It Works

There are **two agent graphs**:
1. `make_default_graph`: Simple ChatOpenAI LLM responds to user input.
2. `make_alternative_graph`: The LLM uses tools (like `add(a, b)`) when appropriate via LangChain's tool calling and LangGraph conditional routing.



