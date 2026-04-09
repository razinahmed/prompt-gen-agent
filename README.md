# Prompt Gen Agent

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![AI](https://img.shields.io/badge/AI-Powered-purple)
![License](https://img.shields.io/badge/License-MIT-green)

An AI-powered prompt generation agent that creates optimized prompts for large language models. Takes a rough idea or task description and produces structured, effective prompts designed to maximize LLM output quality.

---

## Features

- **Prompt Optimization** -- Transforms vague descriptions into precise, effective LLM prompts
- **Template Library** -- Pre-built prompt templates for coding, writing, analysis, and more
- **Chain-of-Thought** -- Generates step-by-step reasoning prompts for complex tasks
- **Role Assignment** -- Automatically crafts system prompts with appropriate personas
- **Few-Shot Examples** -- Builds prompts with relevant examples for better output
- **A/B Testing** -- Generates prompt variants for comparing LLM response quality

---

## Tech Stack

| Technology | Purpose |
|---|---|
| Python 3.9+ | Core runtime |
| LLM API | Prompt refinement engine |
| NLP Pipeline | Text analysis |
| CSS3 | UI theming |
| Makefile | Build and test automation |

---

## Quick Start

```bash
# Clone the repository
git clone https://github.com/razinahmed/prompt-gen-agent.git
cd prompt-gen-agent

# Install dependencies
pip install -r requirements.txt

# Generate an optimized prompt
python main.py --task "Summarize a technical document" --model gpt-4
```

---

## Project Structure

```
prompt-gen-agent/
├── styles/
│   └── theme.css           # UI theme configuration
├── Makefile                # Build and test commands
├── LICENSE                 # MIT License
├── SECURITY.md             # Security policy
└── README.md
```

---

## Usage

```bash
# Build the project
make build

# Run tests
make test
```

---

## Contributing

1. Fork the repository
2. Create a feature branch -- `git checkout -b feature/your-feature`
3. Commit your changes -- `git commit -m "feat: add new feature"`
4. Push and open a Pull Request

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

**Built by [Razin Ahmed](https://github.com/razinahmed)**
