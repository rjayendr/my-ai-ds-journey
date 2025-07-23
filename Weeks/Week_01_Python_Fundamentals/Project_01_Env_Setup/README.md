# Project 01: Personal Coding Environment Setup

## Purpose
This project focuses on establishing a robust and isolated Python development environment using VS Code, Git, and virtual environments. It ensures that all necessary tools are correctly configured for the upcoming AI and Data Science projects.

## Setup Steps Completed
* **VS Code Configuration:** Verified Python extension and general settings.
* **Git Integration:** Configured Git with user credentials and linked to the `my-ai-ds-journey` GitHub repository.
* **Virtual Environment (`.venv`):** Created and configured a project-specific virtual environment to manage dependencies.
* **`.gitignore` Setup:** Implemented `.gitignore` to exclude non-essential files and folders (like `.venv/`) from version control.
* **Initial Project Structure:** Established the foundational folder structure for Week 1 projects.

## How to Verify the Environment
1.  **Open VS Code** in the `my-ai-ds-journey` root folder.
2.  **Open the Integrated Terminal** (`Ctrl+`` ` `).
3.  **Activate the Virtual Environment:** If not already active (check for `(.venv)` in your terminal prompt), run:
    ```bash
    .venv\Scripts\activate.bat   # For Command Prompt or PowerShell in VS Code
    # OR
    source .venv/Scripts/activate # For Git Bash in VS Code
    ```
4.  **Navigate to this project folder:**
    ```bash
    cd Week_01_Python_Fundamentals/Project_01_Env_Setup/
    ```
5.  **Run the test script:**
    ```bash
    python environment_test.py
    ```

## Expected Output
If the environment is set up correctly, you should see the message: `Environment setup successful and verified!`