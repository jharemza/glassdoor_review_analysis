# 🕵️‍♂️ Glassdoor Review Analysis

Analyze Glassdoor reviews for hedge funds to uncover sentiment and patterns related to work culture, leadership, compensation, and more.

## 📦 Project Structure

- `glassdoor_review_analysis.ipynb` — Core analysis notebook performing data cleaning, NLP, and visualization.
- `README.md` — Project overview and usage guide.

## 🧪 Usage

> 📌 Prerequisite: Jupyter Notebook environment (e.g., VS Code with Python extension, JupyterLab)

1. Clone the repository:

   ```bash
   git clone https://github.com/jharemza/glassdoor_review_analysis.git
   cd glassdoor_review_analysis
   ```

2. Open `glassdoor_review_analysis.ipynb` in your notebook interface.
3. Run the cells to perform analysis and generate outputs.

## 📊 Features

- Text cleaning and normalization of review content.
- Exploratory visualizations (rating distributions, word frequencies).
- Sentiment analysis using VADER.
- Keyword-based tagging for themes (e.g., work-life balance, compensation).

## 🔧 Requirements

```bash
pandas
matplotlib
seaborn
nltk
```

Can be installed via:

```bash
pip install pandas matplotlib seaborn nltk

```

Note: This project does not include a requirements.txt file by default.
If you’d like to generate one from an active environment:

```bash
pip freeze > requirements.txt
```

Then later you can reuse it with:

```bash
pip install -r requirements.txt
```

## 📝 License

This project is licensed under the MIT License.
