# 🩺 Patient Satisfaction Sentiment Analysis (NHS-Style Mock Project)

This project showcases how Natural Language Processing (NLP) techniques can be applied to **simulated NHS patient survey data** to evaluate satisfaction, uncover key themes, and support **primary care performance frameworks** like **QOF**, **IIF**, and **Quality Improvement (QI)** initiatives.

Built using **Python**, it combines the power of **NLTK (VADER)** for sentiment scoring and **SpaCy** for keyword extraction. This approach is especially useful for data analysts working in healthcare settings or aspiring to roles in the NHS or primary care environments.

---

## 📌 Key Features

- ✅ **Sentiment Analysis with NLTK's VADER**  
  Classifies patient feedback as *Positive*, *Negative*, or *Neutral* and provides sentiment polarity scores.

- 🧠 **Keyword Extraction with SpaCy**  
  Highlights recurring words and themes across responses to uncover service gaps or strengths.

- 📊 **Clean Tabular Output**  
  Ready for use in Power BI, Tableau, or Excel dashboards for stakeholder reporting.

---

## 📈 Example Use Case

This analysis can be used by:

- **Practice Managers** to monitor patient experience trends  
- **Data Leads** to support IIF and QOF submissions  
- **QI Leads** to target improvements in communication, access, or wait times  
- **NHS Analysts** to support decision-making based on real feedback

For instance, if many patients mention **“waiting times”** or **“rushed appointments,”** the data can inform operational or staffing reviews.

---

## 📂 What’s Included

- `patient_sentiment_analysis.ipynb` – the full annotated notebook  
- `mock_patient_survey.csv` – simulated survey dataset  
- Outputs including:
  - Sentiment category
  - Sentiment score
  - Keyword frequency table

---

## 🛠 Tools & Libraries Used

- **Python**
- **NLTK** – for sentiment analysis  
- **SpaCy** – for NLP & keyword extraction  
- **Pandas** – for data manipulation  
- **Google Colab / Jupyter Notebook**

---

## ✅ Sample Output

| PatientID | SurveyResponse                                      | Sentiment | Score  |
|-----------|-----------------------------------------------------|-----------|--------|
| 1         | The staff were very helpful a
