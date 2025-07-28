# TA x Cricket Data Tool

A Chrome extension that enables users to interact with cricket match data using natural language queries.

## 🚀 Getting Started

1.  **Clone the repository:**
    ```bash
    git clone <repository_url>
    cd ta-cricket-tool
    ```

2.  **Create a virtual environment:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## 📝 Project Overview

This tool leverages a GenAI model to translate natural language questions from users into executable Python scripts that query a cricket database. The results are then returned to the user as text or visualizations.

-   **Frontend:** Chrome Extension
-   **Backend:** Python with Pandas
-   **AI:** Natural Language to Python translation model
-   **Data:** Structured cricket data (CSVs)
