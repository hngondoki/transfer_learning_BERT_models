# Transfer Learning in BERT models
This is an experimental approach to determine factors of success in transfer learning across BERT models with a focus on domain similarity and domain shifts.

The main paper to read is [Exploring Transfer Learning Performance]([Exploring Transfer Learning Performance.pdf](https://github.com/hngondoki/transfer_learning_BERT_models/blob/main/Exploring%20Transfer%20Learning%20Performance.pdf)

Here is the abstract:
Abstract
Transfer learning has emerged as a cornerstone of modern natural language processing (NLP), particularly with transformer-based architectures like BERT and its variants. Despite substantial progress, critical questions remain regarding how best to transfer knowledge across domains, the influence of training data sequences, and the effectiveness of different BERT models in transfer scenarios. In this paper, we investigate the transferability and generalization capability of RoBERTa, DistilBERT, and DeBERTa across related and unrelated domains using the Amazon Reviews dataset. We design three pipelines to analyze domain similarity, sequencing, dataset sizes, and fine-tuning strategies. Our results demonstrate the importance of sequencing, domain similarity, and hyperparameter tuning in optimizing cross-domain performance. DeBERTa shows superior cross-domain transfer, while RoBERTa excels in low-resource fine-tuning. These findings provide practical insights for leveraging transfer learning in real-world NLP applications.
