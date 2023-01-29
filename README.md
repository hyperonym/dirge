# Dirge

Dirge is a collection of foundation models for Natural Language Processing (NLP). This repository contains scripts and notebooks to replicate the models available on Hugging Face [Model Hub](https://huggingface.co/hyperonym).

## Models

### XLM-RoBERTa Longformer

**xlm-roberta-longformer** is a multilingual [Longformer](https://arxiv.org/abs/2004.05150) initialized with [XLM-RoBERTa](https://huggingface.co/xlm-roberta-base)'s weights without further pretraining. It is intended to be fine-tuned on a downstream task.

| Model | attention_window | hidden_size | num_hidden_layers | model_max_length |
| --- | --- | --- | --- | --- |
| [base](https://huggingface.co/hyperonym/xlm-roberta-longformer-base-16384) | 256 | 768 | 12 | 16384 |
| [large](https://huggingface.co/hyperonym/xlm-roberta-longformer-large-16384) | 512 | 1024 | 24 | 16384 |

## License

Dirge is available under the [MIT License](https://github.com/hyperonym/dirge/blob/master/LICENSE).

---

© 2023 [Hyperonym](https://hyperonym.org)
