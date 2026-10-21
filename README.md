# FoodWise ERP

A beginner-friendly restaurant inventory, food waste, supplier, and purchase-order demo built with Flask and SQLite.

## Features
- Dashboard with inventory, low-stock, expiry and waste-cost summaries
- Add, edit and delete ingredients
- Record food waste and automatically reduce stock
- Supplier management
- Purchase orders and reorder recommendations
- Receiving an order updates stock only once
- Sample data is created automatically on first run

## Run locally
1. Install Python 3.10 or newer.
2. Open a terminal in this folder.
3. Create and activate a virtual environment (optional but recommended).
4. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Start the app:

   ```bash
   python app.py
   ```

6. Open http://127.0.0.1:5000

The SQLite database (`foodwise.db`) is created beside `app.py` on first run.

## Project structure
- `app.py` — Flask routes, business logic, database initialization
- `templates/` — HTML pages
- `static/style.css` — responsive styling
- `requirements.txt` — Python dependency
