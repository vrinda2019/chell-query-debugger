# chell-query-debugger
Query-Driven Debugging Framework for Small Language Models

# Chell: Query-Driven Debugging for Small Language Models

**Chell** is an interactive, query-driven debugging system that helps Small Language Models (SLMs) fix logical errors in Python code. It focuses on data analysis tasks using libraries like pandas, NumPy, and Matplotlib.

## ✨ Key Features

- Detects logical errors in code
- Asks clarification questions before fixing
- Uses small language models for lightweight debugging
- Modular design for easy extension

## 🛠 Project Structure

- `chell/` – core modules (error detection, query generation, refinement)
- `examples/` – test scripts and sample bugs
- `data/` – curated debugging dataset
- `notebook/` – dev sandbox in Jupyter
- `results/` – evaluation and metrics

## 🚀 How to Run

```bash
python main.py
