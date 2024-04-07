# Voice of Customer

## Project Overview
This repository hosts a data analysis project based on customer reviews for a Xiaomi smartphone, originally undertaken for a client. It re-creates the analytical process, encompassing sentiment analysis, topic modeling via LDA, and temporal trend visualisation, utilising a dataset sourced from Kaggle by user Abhishek Parve.

## Contents
- `Xiaomi_Feedback_Analysis.ipynb`: The Jupyter notebook containing the analysis workflow.
- `data/`: Folder with the Kaggle dataset used in the analysis (courtesy of Abhishek Parve).
- `requirements.txt`: Python package dependencies for replicating the analysis environment.
- `visualisations/`: Generated charts and plots that visualise insights from the data.

## Getting Started
To replicate this analysis on your machine, follow the steps below:

1. **Clone the Repository**
   ```
   git clone https://github.com/telhouni/voice-of-customer.git
   cd voice-of-customer
   ```

2. **Install Dependencies**
   ```
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**
   ```
   jupyter notebook Xiaomi_Feedback_Analysis.ipynb
   ```

## Repository Structure
- **Data Preparation**: Cleaning and structuring data for analysis.
- **Exploratory Analysis**: Initial data exploration to understand the dataset's structure.
- **Sentiment Analysis**: Applying NLTK to evaluate the emotional tone behind reviews.
- **Sentiment Trend Analysis**: Visualising how customer sentiment fluctuates over time.
- **LDA Topic Modeling**: Extracting themes using Gensim with visualisations by PyLDAvis.
- **Conclusions**: Summarising findings and translating them into actionable business insights.

## Contribution
Suggestions and contributions are welcome. Please feel free to fork the repository, make changes, and submit a pull request.

## License
This project is made available under the MIT License - see the LICENSE.md file for details.

## Acknowledgments
- Gratitude to Kaggle and Abhishek Parve for providing the dataset that made this analysis possible.
