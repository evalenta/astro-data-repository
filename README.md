# AstroDataAnalysis

Astronomy data analysis exercises and pedagogy notebooks.

## Repository structure

- **Exercises/** — Jupyter notebooks, images, and environment config (`.env`) for running the exercises.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/AstroDataAnalysis.git
   cd AstroDataAnalysis
   ```

2. Create and activate a virtual environment (recommended):
   ```bash
   python -m venv venv
   # Windows:
   venv\Scripts\activate
   # macOS/Linux:
   # source venv/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. If the exercises use API keys or secrets, add a `.env` file in `Exercises/` with the required variables (see your course materials for the expected format).

## Running the notebooks

From the repo root:

```bash
jupyter notebook Exercises/
```

Or open the `.ipynb` files in Jupyter Lab, VS Code, or Cursor.

## Publish to GitHub

To create the GitHub repository **AstroDataAnalysis**:

1. On GitHub, create a new repository named `AstroDataAnalysis` (do not add a README or .gitignore there).
2. In this folder, run:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: exercises and pedagogy notebooks"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/AstroDataAnalysis.git
   git push -u origin main
   ```
   Replace `YOUR_USERNAME` with your GitHub username.

## License

[Add your license here.]
