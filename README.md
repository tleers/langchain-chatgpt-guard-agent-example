This ChatGPT agent can reason, interact with tools, be constrained to specific answers and keep a memory of all of it.

All credit goes to Langchain, OpenAI and its developers!

# Fully fledged ChatGPT Agent

Langchain is releasing updates faster than the speed of light, but to use the currently in PR-mode Guard & ChatAgent functionalities, I merged the latest master branch with the guard & chat-agent branches.

```
pip install wikipedia openai python-dotenv google-search-results
git clone https://github.com/tleers/langchain
cd langchain
git checkout merge/guard_and_chat
pip install -e .
```

Python version I tested this with is 3.9.6.
I'll add in some proper reproducibility support later, for now this will do.