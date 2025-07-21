

## 📊 Google Search Analysis with Python

This project leverages the **PyTrends** library to extract and visualize Google Trends data for various keywords. It's a practical application of **data analytics** for identifying trends, comparing interest over time, and understanding regional interest for specific search terms.

### 🔍 Project Objectives

* Automate Google Trends data extraction using Python.
* Visualize keyword popularity across top 15 countries.
* Create an interactive **world map (choropleth)** showing regional interest.
* Analyze **time-wise search trends** for a keyword.
* Compare **multiple keywords** to understand changing interests.

### 📌 Features

* 📈 Keyword-wise global interest analysis
* 🌍 Interactive choropleth maps using Plotly
* 🕒 Time-series plots of keyword popularity
* 🔄 Easy keyword swapping for flexible analysis
* 📊 Multi-keyword comparison with line charts

### 🛠️ Tools & Libraries Used

* Python
* [PyTrends](https://github.com/GeneralMills/pytrends)
* Matplotlib
* Seaborn
* Plotly
* Pandas

### ⚙️ How to Use

1. Install dependencies:

   ```bash
   pip install pytrends matplotlib seaborn plotly pandas
   ```
2. Update the keyword in the script:

   ```python
   keyword = "cloud computing"
   ```
3. Run the script to:

   * Generate bar charts of top countries.
   * Plot a choropleth world map.
   * Show trends over the past year.
   * Compare search interest for multiple keywords.

### 📈 Use Cases

* Market research
* SEO analysis
* Product demand forecasting
* Political/public interest tracking


