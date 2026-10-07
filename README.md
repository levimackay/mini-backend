# MINI BACKEND
In order to practice for job interviews and live coding sessions, I challenged myself to make a backend from scratch.
I wanted to see what was the fastest, most effective, and easiest to set up.

## Stack
FastAPI for the web framework and uv for Python and dependencies.

## Run it
```sh
uv run fastapi dev main.py
```

Then check that it's up:
```sh
curl http://127.0.0.1:8000/health
```

It returns `{"result": "healthy"}`.
