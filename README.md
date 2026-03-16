# Mini ML Workflow

Machine learning projects usually involve many steps and tools, and each step can easily become a project on its own. This repository provides a **minimal, structured overview of a typical machine learning workflow**.

The goal is **not to cover everything**, but to show the **essential stages of a real ML pipeline** in a simple and easy-to-follow way.

Each step is presented in a compact form with optional deeper explanations so learners can understand:

- where each step fits in the workflow  
- why the step is necessary  
- what typical methods or tools are used  

The repository walks through the core stages of an ML project:

1. **Getting the data**
2. **Exploratory Data Analysis (EDA)**
3. **Data cleaning**
4. **Preprocessing**
5. **Modeling**
6. **Evaluation**
7. **Iterate/Improve or Save**


## Setup
1) Extract the data from the `data.zip` file.
2) Install the required libraries:


### **`macOS`** type the following commands : 

- Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
### **`WindowsOS`** type the following commands :

- Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :
    ```
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```