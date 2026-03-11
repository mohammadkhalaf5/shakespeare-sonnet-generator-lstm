# Shakespeare Sonnet Generator using LSTM

This project builds a deep learning language model capable of generating
Shakespeare-style sonnets using a Long Short-Term Memory (LSTM) neural network.

The model is trained on a dataset of Shakespeare's sonnets and learns
language patterns to predict the next word in a sequence, allowing it to
generate new poetic text.

---

## Technologies Used

- Python
- TensorFlow
- NumPy
- Matplotlib
- Natural Language Processing (NLP)

---

## Project Workflow

1. Load and preprocess Shakespeare's sonnet dataset
2. Convert text into numerical representations using TensorFlow TextVectorization
3. Generate n-gram sequences from the text
4. Pad sequences to equal length
5. Train an LSTM neural network to predict the next word
6. Generate new text based on a seed phrase

---

## Model Architecture

Embedding Layer  
LSTM Layer (128 units)  
Dense Output Layer with Softmax activation

The model learns the probability distribution of the next word in a sequence.

---

## Training

The model was trained for 30 epochs on the Shakespeare sonnet dataset.

Training metrics such as loss and accuracy were tracked during training.

---

## Example Generated Text

Seed prompt:

"love is a smoke"

Generated continuation:

love is a smoke made with the fume of sighs  
that wander through the silent night and air  
the heart remembers what the mind denies  
a fleeting dream too delicate to bear  

*(Example output – actual output varies each run.)*

