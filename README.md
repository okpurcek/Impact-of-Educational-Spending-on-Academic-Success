# Analyzing the Impact of Educational Expenditures on Academic Success in Higher Education

## Introduction
This project aims to investigate the relationship between financial investments in Higher Education Institutions (HEIs) and their academic success. Specifically, we analyze how expenditures for HEIs and expenditures per student correlate with academic outputs such as the number of articles published in international journals, patent applications, citations, and world university rankings. Additionally, we examine the impact of inflation on educational expenditures over the years.

## Project Objectives
- Identify patterns and correlations between financial inputs and academic achievements in HEIs.
- Examine the impact of per-student educational expenditure on research outputs.
- Investigate the influence of inflation on educational investments over time.
- Provide data-driven insights for policymakers and institutional decision-makers.
- Analyze university ranking trends over the years.
- Evaluate patent filings and R&D investments as indicators of academic success.

## Dataset Sources
The project utilizes multiple datasets from reputable sources:

1. **Turkish Statistical Institute (TUIK) - Education Expenditure and Inflation Statistics (2019-2022)**
   - Data on total and per-student expenditures in higher education.
   - Inflation statistics that affect financial stability in education.
   - Breakdown of educational spending (operational, capital, research, etc.).
   - URL: [https://data.tuik.gov.tr](https://data.tuik.gov.tr)

2. **Council of Higher Education (YÖK) - University Monitoring and Evaluation Reports**
   - University-specific budget allocations, faculty ratios, and research statistics.
   - Performance indicators like number of published papers, citations, and patents.
   - URL: [University Monitoring and Evaluation Reports](https://www.yok.gov.tr/universiteler/izleme-ve-degerlendirme-raporlari)

3. **Council of Higher Education (YÖK) - General Reports (2019-2022)**
   - Faculty-to-student ratios, research outputs, and institutional rankings.
   - Number of doctoral students and graduates.
   - National and international research collaboration statistics.
   - URL: [2022 University Monitoring and Evaluation General Report](https://www.yok.gov.tr/Documents/Yayinlar/Yayinlarimiz/2022/2022-universite-izleme-ve-degerlendirme-genel-raporu.pdf)

## Methodology
1. **Data Collection & Cleaning**
   - Gather financial and academic performance data from various sources.
   - Standardize and clean datasets for consistency.
   - Convert inflation-adjusted values for accurate comparisons over time.

2. **Exploratory Data Analysis (EDA)**
   - Identify key trends and relationships in the data.
   - Use statistical summaries and visualizations to understand distributions.
   - Compare universities based on expenditure, research output, and rankings.

3. **Statistical Analysis & Modeling**
   - Correlation analysis to determine relationships between financial inputs and academic outputs.
   - Regression models to quantify the impact of expenditures on academic success.
   - Time-series analysis to track trends over the years.
   - Clustering techniques to group universities based on funding and performance similarities.

4. **Visualization & Reporting**
   - Generate interactive data visualizations to support findings.
   - Summarize results with actionable insights and policy recommendations.
   - Develop comparative charts for university rankings and financial investments.

## Installation & Setup
To run this project locally, follow these steps:

### Prerequisites
Ensure you have Python installed along with the following libraries:
```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels
```

### Clone the Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### Run the Jupyter Notebook
Use the following command to launch Jupyter Notebook and explore the data:
```bash
jupyter notebook yzv211project.ipynb
```

## Project Structure
```
.
|-- datasets/              # Data files (CSV, XLS, PDF reports)
|-- README.md              # Project documentation
|-- requirements.txt       # Dependencies
```

## Results & Findings
- **Academic performance is significantly correlated with per-student expenditure.**
- **Inflation-adjusted expenditures provide a more accurate measure of investment trends.**
- **Universities with higher R&D spending tend to have more publications in top-tier journals.**
- **Patent applications and granted patents show an increasing trend over the years.**
- **University rankings fluctuate based on financial stability and research productivity.**

## Future Work
- Expanding the dataset to include more universities and years.
- Applying machine learning techniques to predict future trends.
- Conducting cross-country comparisons to benchmark performance.
- Exploring additional indicators like faculty salaries and student success rates.

## Contributors
- **Oğuz Kağan Pürçek** - Istanbul Technical University
- **Umut Çalıkkasap** - Istanbul Technical University

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
We acknowledge the Turkish Statistical Institute (TUIK) and the Council of Higher Education (YÖK) for providing the necessary data.

