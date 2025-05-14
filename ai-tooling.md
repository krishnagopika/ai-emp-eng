# AI Tooling

## AI Tools for Code Generation

GitHub Copilot is an AI-powered coding assistant developed by GitHub and OpenAI. It supports multiple languages and IDEs (VS Code, JetBrains, Neovim) and helps developers by suggesting entire lines or blocks of code based on natural language or existing code context.

**other tools:**

- Claude code
- Coduium Qodo
- Blackbox

---

## GitHub Copilot

### Features

- **Code Completion**  
  Autocompletes code snippets, entire lines, or functions based on context and best practices.

- **Chat**  
  Interactive chat interface ("Copilot Chat") where developers can ask questions, get help with code, understand errors, or receive explanations and suggestions.


### `/generate`

- Used in chat to generate code based on natural language prompts.  
- Example:  
  `/generate create a Python function to calculate Fibonacci numbers`


### `/edit`

- Modifies selected code snippets or files according to user instructions.  
- Example:  
  `/edit make this function more efficient`


### `/explain`

- Explains what a selected code block does.  
- Example:  
  `/explain what does this recursive function do?`


### `/fix`

- Suggests or applies bug fixes to a selected code block.  
- Example:  
  `/fix this function throws an index error`


### `/tests`

- Generates unit tests or integration tests for functions or files.  
- Supports common testing frameworks (e.g., JUnit, PyTest, Mocha).  
- Example:  
  `/tests generate tests for this Java method`


### `/doc`

- Creates inline documentation or docstrings.  
- Adheres to language-specific formats (e.g., Python docstrings, Javadoc).  
- Example:  
  `/doc add docstring to this function`

---

## Context

Copilot uses:

- **File context** – Looks at surrounding code to offer suggestions.  
- **Project context** – (in supported environments) Understands multiple files to provide cohesive results.  
- **Natural language** – Interprets plain English instructions or comments.

## Agents

- **GitHub Copilot Agents** (beta/experimental):  
  - Combine chat + task automation using predefined commands like `/generate`, `/fix`, `/explain`, etc.  
  - Act as "developer assistants" within the IDE.  
  - Capable of reasoning across files and following multi-step instructions.
  - Supports MCP severs


- [copilot](https://github.com/copilot)
- [copilot plans](https://github.com/features/copilot/plans)




