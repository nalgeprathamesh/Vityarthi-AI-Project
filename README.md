# World Atlas Master Quiz for VITyarthi Project

Name - Prathamesh Nalge
Reg No - 25BCY10012
Subject - Fundamentals of AI and ML

A command-line Geography Quiz Master built using the Gemini API to take users on an exciting, 10-question global adventure.
The quiz questions range in difficulty and challenge the user to guess a country or capital based on GeoGuessr-style descriptions (landmarks, climate, cultural clues) or flag/symbol details.

### Prerequisites

* Python (3.7+)
* A Gemini API Key from [Google AI Studio](https://ai.google.dev/gemini-api/docs/api-key)

### Installation(for linux users as I have use Kali linux(based on Debian)

1.  **Clone the repository:**
    ```zsh
    git clone https://github.com/nalgeprathamesh/Vityarthi-AI-Project
    cd Vityarthi-AI-Project
    ```

2.  **Install the necessary libraries:**
    ```zsh
    pip install google-genai
    ```
    *(Note: The provided code snippet uses `google.genai`, which corresponds to the `google-genai` library.)*

3.  **Set Your API Key**

    The program requires your Gemini API key to be set as an environment variable.

    **On Linux/macOS:**
    ```zsh
    export GEMINI_API_KEY="YOUR_API_KEY"
    ```

    **On Windows (Command Prompt/Powershell):**
    ```
    set GEMINI_API_KEY="YOUR_API_KEY"
    ```

### Running the Quiz

Execute the Python script to start your global quest:

```
python main.py
