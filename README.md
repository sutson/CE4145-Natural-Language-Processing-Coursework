# CE4145-Natural-Language-Processing-Coursework
## Author: Wilson Sutherland (2227555)

### Dataset Information
The dataset used was the [Game Reviews Sentiment](https://huggingface.co/datasets/auphong2707/game-reviews-sentiment) dataset. This was first accessed from Hugging Face on 25th October, 2025.

### Repository Information
This repository features two files:
- `CE4145 NLP - Binary Classification.ipynb`
  - This contains the main code for the coursework, performing binary classification on the dataset.
- `CE4145 NLP - Multiclass Classification (Supplementary).ipynb`
  - This is a supplementary notebook referred to in the main one where multi-class classification is attempted, ultimately proving unsuccessful.

### Necessary Files
For **GloVe** embeddings to work, you must download the `glove.6B.zip` file from https://nlp.stanford.edu/projects/glove/. Once extracted, the `glove.6B.100d.txt` file should be placed in the `main_filepath` directory specified early in the notebook.

### Other Information
At various points in the code, there are lines commented out with text to explain why this is the case. For example, the code for converting the GloVe embeddings to a Word2Vec format (required by gensim) is commented out, but this must be run at least once for the following code cells to function properly.