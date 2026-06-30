# NLP-BERT-GPT-GAN-Comparison

A comparative NLP project implementing and evaluating BERT, GPT-2, and Text GAN models using the IMDB Movie Review Dataset.

## Dataset
IMDB Large Movie Review Dataset  
https://huggingface.co/datasets/stanfordnlp/imdb

## Models Implemented
- BERT – Sentiment Classification
- GPT-2 – Text Generation
- Text GAN – Adversarial Text Generation

## Results

| Model | Task | Key Metric |
|---------|---------|---------|
| BERT | Sentiment Classification | F1-Score: 0.91 |
| GPT-2 | Text Generation | Average Loss ≈ 3.5 |
| Text GAN | Adversarial Text Generation | Discriminator Accuracy ≈ 0.999 |

## Repository Contents
- Data preprocessing and dataset preparation (performed within the notebook)
- Model training pipelines
- Training histories
- Evaluation metrics
- Test inferences
- Final project report

## Technologies Used
- Python
- PyTorch
- Hugging Face Transformers
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab
