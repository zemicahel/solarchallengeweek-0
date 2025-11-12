Got it! Since your **main script is `main.py`** and `utils.py` is inside an **`app/` folder**, here’s a **README.md** updated to reflect that structure:

```markdown
# 🌞 Cross-Country Solar Farm Dashboard

This project provides an interactive **Streamlit dashboard** for analyzing solar farm data across multiple countries using cleaned CSV datasets. The dashboard allows users to explore solar metrics, visualize distributions, and view summary statistics for selected countries.

---

## 🗂 Project Structure

```

project/
├── app/
│   ├── main.py          # Main Streamlit dashboard script
│   └── utils.py         # Helper functions: load_data, boxplot_metric, summary_table
├── clean/               # Folder containing cleaned CSV files
│   ├── benin_clean.csv
│   ├── sierraleone_clean.csv
│   └── togo_clean.csv
├── README.md
└── requirements.txt

````

---

## 🚀 Features

- **Multi-country selection:** Compare Benin, Sierra Leone, and Togo (or any subset) interactively.
- **Metric visualization:** Select a metric (`GHI`, `DNI`, `DHI`, `Tamb`) to display as a **boxplot** across countries.
- **Summary statistics:** View a table with **mean, median, and standard deviation** for each metric per country.
- **Cleaned dataset usage:** All analysis is performed on pre-processed, cleaned CSV files.

---

## 🛠 Installation

1. Clone the repository:



````

2. Create a virtual environment and activate it:

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ⚡ Running the Dashboard

Start the Streamlit app:

```bash
streamlit run app/main.py
```

Open the link provided by Streamlit in your browser (usually `http://localhost:8501`).

---

## 🧩 Usage

1. Select the countries to display in the sidebar.
2. Choose a solar metric (`GHI`, `DNI`, `DHI`, `Tamb`) from the dropdown.
3. The dashboard will display:

   * A **boxplot** showing the distribution of the selected metric across countries.
   * A **summary table** with mean, median, and standard deviation of each metric.

---

## 📝 Functions Overview (from `app/utils.py`)

* `load_data(path)`: Loads cleaned CSV data with timestamp parsing.
* `boxplot_metric(df, metric)`: Generates a boxplot for a selected metric.
* `summary_table(df, metrics)`: Returns a summary table grouped by country.

---

## 📂 Notes

* Ensure the `clean/` folder contains the cleaned CSV files named appropriately:

  * `benin_clean.csv`
  * `sierraleone_clean.csv`
  * `togo_clean.csv`
* If a CSV file is missing, the dashboard will display a demo dataset.

---

## 🔗 Contact

For questions or feedback, reach out to **[Zemicahel Abraham,]** at **[[zemicahela@gmail.com](mailto:zemicahela@gmail.com)]**.

```

---

If you want, I can also make a **shorter, GitHub-ready version** that’s **more visually appealing** with badges, emojis, and a demo GIF/preview section.  

Do you want me to do that?
```
