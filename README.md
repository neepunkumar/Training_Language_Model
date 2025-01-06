# Character-Level Language Model

In this repository, we train a language model on a small corpus and use it to generate new text in the same style. The model learns the conditional probability of the next character in a sequence given the characters up until the current time. To achieve this, we use an **LSTM (Long Short-Term Memory)** network.

---

## Features
- **Character-level language modeling:** Learn character sequences to generate coherent text.
- **Conditional probability modeling:** Predict the next character based on previous context.
- **LSTM Implementation:** Use an LSTM-based architecture for efficient sequence modeling.

---

## How It Works
1. **Training:** 
   - The model is trained on a small corpus.
   - It learns the statistical patterns of character sequences in the text.

2. **Generation:**
   - The trained model generates new text character by character, maintaining the style of the training data.

---

## File Structure
- `notebooks/`: Contains Jupyter notebook for implementation.
- `data/`: Stores the training corpus.

---

## Requirements
To run the project, you'll need the following:
- Python 3.8+
- Required libraries:
  - `numpy`
  - `torch` (PyTorch)
  - `torchtext`
  - `matplotlib`

Install the libraries using:
```bash
pip install -r requirements.txt
