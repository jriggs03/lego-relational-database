# LEGO Relational Database

Loads LEGO data into linked SQL tables.

Course project for CSC 365 at Cal Poly. Built with Python, pandas, and SQLite.

## What it does

Inspects and cleans LEGO CSV tables, defines a relational schema, enables foreign-key enforcement, loads records, and queries relationships between sets, parts, colors, inventories, and themes.

## Run

Open `lego_database.ipynb` in Google Colab. Supply the original LEGO CSV files under `/content/archive/`: `colors.csv`, `inventories.csv`, `inventory_parts.csv`, `inventory_sets.csv`, `part_categories.csv`, `parts.csv`, `sets.csv`, and `themes.csv`. Run the cells in order.

The notebook preserves the original course workflow. SQLite is included in Python; the original `db-sqlite3` installation cell is unnecessary. Data files and executed outputs are omitted. This cleanup has not rerun the full notebook.
