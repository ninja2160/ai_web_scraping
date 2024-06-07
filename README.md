

## Setup

### 1. Create a new Python virtual environment

`python -m venv virtual-env` or `python3 -m venv virtual-env` (Mac)

`py -m venv virtual-env` (Windows 11)

### 2. Activate virtual environment

`.\virtual-env\Scripts\activate` (Windows)

`source virtual-env/bin/activate` (Mac)

### 3. Install dependencies using Poetry

Run `poetry install --sync` or `poetry install`

### 4. Install playwright

```bash
playwright install
```

### 5. Create a new `.env` file to store OpenAI's API key

```text
OPENAI_API_KEY=XXXXXX
```

## Usage

### Run locally

```bash
python main.py
```
