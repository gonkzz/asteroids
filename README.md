# Asteroids

An Asteroids game built with [pygame](https://pyga.me/).

## Running the game

The easiest way is with [uv](https://docs.astral.sh/uv/), which sets up Python and the dependencies for you:

```bash
uv run main.py
```

Install uv:

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

### Without uv

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python main.py
```

## Controls

| Key   | Action        |
|-------|---------------|
| W     | Move forward  |
| S     | Move backward |
| A     | Rotate left   |
| D     | Rotate right  |
| Space | Shoot         |
