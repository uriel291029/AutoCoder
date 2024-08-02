# AutoCoder

Autocoder is a CLI utility that connects to OpenAI's ChatGPT, sends it the current project structure so the AI has some context and then listens for prompts for programming requirements from the user. The AI sends operations to the user's computer through the CLI and they're being executed, modifying the source code directly.

The AI is able to create, update and delete source files. It's also able to read files in case it needs more context to solve the issue. It's also able to execute shell scripts (seeking approval from the user first)
