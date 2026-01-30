Small Language Model (SLM) – Tiny Stories
=========================================

This project demonstrates how to design and train a compact Small Language Model (SLM) from scratch
using the Tiny Stories dataset on Hugging Face. The goal is to show that even lightweight transformer
models can generate coherent, creative short-form narratives with improved fluency.

Project Highlights
------------------
- Custom Tokenization: Built a tokenizer tailored for short narrative text
- Transformer Architecture: Designed a compact transformer model optimized for small-scale training
- Training Loop: Implemented a custom training pipeline with Hugging Face integration
- Output Quality: Generated fluent and creative short stories despite limited model size

Tech Stack
----------
- Python
- PyTorch
- Hugging Face Transformers & Datasets
- Custom Tokenizer Implementation

Usage
-----
1. Clone the repository:
   git clone https://github.com/your-username/slm-tiny-stories.git
   cd slm-tiny-stories

2. Install dependencies:
   pip install -r requirements.txt

3. Train the model:
   python train.py --dataset tinystories --epochs 10 --batch_size 32

4. Generate stories:
   python generate.py --prompt "Once upon a time"

Example Output
--------------
Prompt:
Once upon a time, a little bird...

Generated Story:
"Once upon a time, a little bird wanted to fly higher than the clouds. It tried every day, learning
from the wind, until one morning it soared above the trees, proud and free."

Learning Outcomes
-----------------
- End-to-end understanding of building a language model from scratch
- Exploring trade-offs between model size and narrative quality
- Applying transformer architectures in a compact setting
- Experimenting with custom tokenization strategies for domain-specific datasets

License
-------
MIT License. Free to use and adapt.
