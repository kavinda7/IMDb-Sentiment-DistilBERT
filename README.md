# IMDb Sentiment Analysis with DistilBERT

This repository contains a Jupyter Notebook that demonstrates how to fine-tune the **DistilBERT** model on the **IMDb movie reviews dataset** for sentiment analysis. The notebook utilizes **Hugging Face Transformers**, **datasets**, and **Comet ML** for experiment tracking.

## Features
- Loads the IMDb dataset using the Hugging Face `datasets` library.
- Tokenizes text using `AutoTokenizer`.
- Fine-tunes a `distilbert-base-uncased` model.
- Uses **Hugging Face Trainer API** for training and evaluation.
- Logs metrics and training progress to **Comet ML**.

## Installation
Ensure you have Python 3.7+ installed. Then, install the required dependencies:

```bash
pip install comet-ml datasets transformers scikit-learn
```

## Usage
### 1. Clone the repository
```bash
git clone https://github.com/your-username/imdb-sentiment-analysis.git
cd imdb-sentiment-analysis
```

### 2. Run the Jupyter Notebook
Launch Jupyter Notebook and open `Prepared_Notebook.ipynb`:
```bash
jupyter notebook
```
Execute the cells sequentially to:
- Load the dataset
- Tokenize text
- Train the model
- Evaluate performance

## Tracking with Comet ML
To log experiments with Comet ML, create an account at [Comet ML](https://www.comet.ml/) and add your API key to the notebook.

## Expected Results
The model should achieve a competitive accuracy on the IMDb dataset. Training logs and metrics will be stored in Comet ML.

## Contributing
Feel free to submit a pull request if you find any improvements!

## License
MIT License
