# AWSM WATSONYOURMIND API

This is a Python project that uses FastAPI to provide endpoints for retrieving available processing models and processing files to return entities.

## Endpoints

### GET /models

Retrieves the list of available processing models.

### POST /process/

Processes a file and returns the extracted entities.

### 🗂 Assets

The following assets are defined by the project.

| File | Source | Description |
| --- | --- | --- |
| [`assets/en_ner_proglang-0.0.0.tar.gz`](https://ibm.box.com/s/u9rwbb60dcxreaiudwht73q02jw9umve) | Local | trained model |

## Setup

Before starting the project, make sure to add the model package into the `assets` directory.


### Installation

1. Clone the repository:
    ```bash
    git clone <repository-url>
    cd my_project
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### Running the Project

Start the FastAPI server:
```bash
weasel run serve 


