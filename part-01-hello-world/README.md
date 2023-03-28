## Part 1 Local Setup

1. `pip install poetry` (or safer, follow the instructions: https://python-poetry.org/docs/#installation)
2. Install dependencies `cd` into the directory where the `pyproject.toml` is located then `poetry install`
3. [UNIX]: Run the FastAPI server via poetry with the bash script: `poetry run ./run.sh`
4. [WINDOWS]: Run the FastAPI server via poetry with the Python command: `poetry run python app/main.py`
5. Open http://localhost:8001/

To stop the server, press CTRL+C

If you get stuck, checkout the [troubleshooting readme](../troubleshooting/README.md)

## Part 1 Local Setup

1. `pip install poetry` (or safer, follow the instructions: https://python-poetry.org/docs/#installation)
2. Install dependencies `cd` into the directory where the `pyproject.toml` is located then `poetry install`
3. Running

`poetry run ./run.sh`
Open http://localhost:8001/

`python app/main.py`
Open http://localhost:8001/

`uvicorn app.main:app --reload`
Open http://127.0.0.1:8000

