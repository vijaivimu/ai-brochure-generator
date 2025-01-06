# AI-Powered Brochure Generator

An intelligent tool designed to scrape and navigate company websites, extract relevant content, and generate professional brochures. This project combines the power of web scraping and AI-driven summarization to automate brochure creation, saving time and effort for businesses and marketers.

---

## Features

1. **Web Scraping:**
   - Fetches content from company websites using `requests` with proper headers.
   - Processes HTML with `BeautifulSoup` to extract meaningful text.
   - Filters out irrelevant elements like scripts, styles, and images.

2. **Content Summarization:**
   - Utilizes AI models to summarize website content intelligently.
   - Supports multiple AI backends for summarization:
     - **Ollama 3.2**: Locally running AI model.
     - **OpenAI GPT-4o Mini**: Cloud-based summarization using OpenAI's API.
   - Customizable system and user prompts for tailored outputs.

3. **Brochure Generation:**
   - Outputs structured summaries ready for professional brochure design.
   - Formats the content in Markdown for easy editing and adaptation.

---

## Technologies Used

- **Python**: Core programming language.
- **Jupyter Notebook**: Development environment.
- **BeautifulSoup**: HTML parsing and content extraction.
- **OpenAI GPT Models**: Summarization of website content (via GPT-4o Mini).
- **Ollama 3.2**: Locally running AI model for summarization.
- **Conda**: Dependency and environment management.

---

## Project Structure

- main_ollama.ipynb       # Notebook for using Ollama 3.2 locally
- main_openai.ipynb       # Notebook for using OpenAI GPT-4o Mini
- environment.yml         # Conda environment file for dependency setup
- .env                    # Stores OpenAI API key securely
- README.md               # Project documentation (this file)
