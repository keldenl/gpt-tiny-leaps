# gpt-tiny-leaps
Tiny proof of concept python apps that use OpenAI's GPT library.

## Tiny Leaps
- **Python Auto Coder** - Mini AutoGPT-like agent-based completion, but specifically writing **VALID** python code. It'll write the code requested, run it, and if there's an error or the results aren't what you expect, it'll use that information to retry. NOTE: This will currently loop forever, so please be careful and make sure to stop it with `ctrl+c` before either u run out of money or your computer goes boom from local llm.

## Local LLM
You can very easily use all these scripts with local LLMs like llama/redpajama/dolly. Just head over to my other project [https://github.com/keldenl/gpt-llama.cpp](https://github.com/keldenl/gpt-llama.cpp) to get set up – it allows for any gpt-powered apps to run off local LLMs.