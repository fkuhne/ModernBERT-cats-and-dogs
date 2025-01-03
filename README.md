# Fine-tuning ModernBERT

This is a simple yet practical example on how to train [ModernBERT](https://huggingface.co/blog/modernbert) to classify texts. For this I've created a small, synthetic dataset called [`cats-and-dogs`](https://huggingface.co/datasets/fkuhne/cats-and-dogs) with three classes: `cats`, `dogs`, and `undefined`.

The trained model is [published at Hugging Face](https://huggingface.co/fkuhne/ModernBERT-cats-and-dogs) and if you don't want to train it again and just run inferences on it you can run the [`inference.ipynb`](./inference.ipynb) notebook.

The dataset was created with https://huggingface.co/spaces/argilla/synthetic-data-generator.


## Training

1. `python3 -m venv .venv`
2. `pip install -r requirements.txt`
3. Run the [`training.ipynb`](./training.ipynb) to train the model.

> **NOTE**: If you don't have a good GPU, run it in [Colab](https://colab.research.google.com).


## Inference

Run the [`ìnference.ipynb`](./inference.ipynb) notebook to run some tests. The test sentences there were generated with GPT-4o.


## References
- https://huggingface.co/blog/modernbert.
- https://huggingface.co/blog/davidberenstein1957/fine-tune-modernbert-on-synthetic-data.
- https://www.philschmid.de/fine-tune-modern-bert-in-2025.
- https://huggingface.co/answerdotai/ModernBERT-base.

