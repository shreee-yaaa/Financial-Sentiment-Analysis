# Financial-Sentiment-Analysis
Financial Sentiment Analysis on Financial PhraseBank datasets classifying financial sentences into positive, neutral, and negative sentiments.

# Project Goal
The goal is to classify financial sentences into **positive**, **neutral**, or **negative** sentiments to aid financial analysis and decision-making.

## Dataset

The dataset combines two datasets:

- **FiQA Dataset**: Contains financial text snippets with sentiment labels.
- **Financial PhraseBank**: A corpus of financial news phrases annotated with sentiments.

The data provides financial sentences along with their sentiment labels to help advance research in financial sentiment analysis.

### Sample Data

| Sentence                                                                                     | Sentiment  |
| -------------------------------------------------------------------------------------------- | ---------- |
| The GeoSolutions technology will leverage Benefon's GPS solutions by providing Location Based Search... | positive   |
| $ESI on lows, down $1.50 to $2.50 BK a real possibility                                     | negative   |
| For the last quarter of 2010, Componenta's net sales doubled to EUR131m from EUR76m for the same period... | positive   |

##  Tech Stack

- **RNN Model**: LSTM,NLP
- **Language**: Python (Jupyter Notebook)
- **Libraries**: `pandas`,`sklearn`, `numpy`, `tensorflow`,`keras`
- **Data**: Financial review dataset with labeled Sentiments : positive,neutral,negative
- **Methods**:
- Text preprocessing and cleaning
- Embedding 
- Data Balance
- Sentiment classification using LSTM / NLP techniques
- Performance evaluation (accuracy, precision, recall, F1-score)
---

## 📂 Files

| File                          | Description                                       |
|-------------------------------|---------------------------------------------------|
| `FinancialSentiment.ipynb`            | Jupyter notebook for data processing, model building and evaluation |
| `fiancial_data.xlsx`         | Training data with two colums: Sentence,Sentiment |
| `README.md`                   | Project documentation                             |


##  Results
Achieved 91.23 % accuracy
