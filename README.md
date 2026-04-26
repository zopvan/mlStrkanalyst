# mlStrkanalyst

A machine-learning stock analyst project that can be run locally (without Google Colab).

## Setup

### Prerequisites

- Python 3.8+
- pip

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/zopvan/mlStrkanalyst.git
   cd mlStrkanalyst
   ```

2. (Optional) Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux / macOS
   venv\Scripts\activate      # Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the main analysis script:

```bash
python main.py
```

## Project Structure

```
mlStrkanalyst/
├── main.py          # Entry point
├── requirements.txt # Python dependencies
└── README.md        # This file
```

## Running without Google Colab

All notebooks and analysis scripts are designed to run as plain Python files.
No Google Colab-specific setup (e.g. `google.colab` imports or `drive.mount`) is used.
