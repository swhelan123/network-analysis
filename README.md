# Network Analysis (COMP30850)

Coursework, notes and data for UCD COMP30850 — Network Analysis.

## Layout

| Folder | Contents |
| --- | --- |
| `Lectures/` | Lecture slide decks (PDF), topics 01–11 |
| `Lab Notebooks/` | Instructor lab notebooks, grouped by week, plus their datasets |
| `Labs/` | Lab task notebooks (Lab 01–06) and accompanying data |
| `Assignments/` | Assignment 1 notebook, data, Gephi project and exported graphs |
| `Exams/` | Sample exam, final exam submission, and revision notebooks |
| `Random Code/` | Scratch NetworkX experiments |

## Tooling

Notebooks run on Python 3.11 with `networkx`, `pandas`, `numpy` and `matplotlib`.
Gephi is used for the `.gephi` project files; `.gexf` graphs can be opened in
either Gephi or NetworkX.

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install networkx pandas numpy matplotlib jupyterlab
jupyter lab
```

Virtual environments are not tracked — see `.gitignore`.
