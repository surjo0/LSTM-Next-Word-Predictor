# LSTM Next Word Predictor

This project is a Next Word Prediction model built using Long Short-Term Memory (LSTM) networks. It predicts the next word in a sentence based on learned patterns from textual data.

## How It Works

1. The model is trained on a dataset of text sequences.
2. It learns word relationships and context through embeddings.
3. Given an input phrase, the LSTM network predicts the most likely next word.

## Model Architecture

- **Embedding Layer**: Converts words into dense vector representations.
- **LSTM Layers**: Capture sequential dependencies in the text.
- **Dense Layer**: Outputs probabilities for possible next words.

## Accuracy & Performance

- The model's accuracy depends on the dataset size and training time.
- It improves with more training and fine-tuning of hyperparameters.
- Can handle short and medium-length text sequences effectively.

## How to Use

1. Clone the repository and install dependencies.
2. Open the Jupyter Notebook.
3. Train the model on your dataset or use a pre-trained version.
4. Enter a text prompt, and the model will suggest the next word.

## Contributions

Suggestions and improvements are welcome! Feel free to open an issue or submit a pull request.
