# CodeClone finetuning [WIP]
In this folder we show how to train an autoregressive on [CodeClone](https://huggingface.co/datasets/code_x_glue_cc_clone_detection_big_clone_bench) dataset, for the binary classification problem of code equivalence prediction. We use Hugging Face [Trainer](https://huggingface.co/docs/transformers/main_classes/trainer) which supports distributed training on multiple GPUs.

## Setup

First login to Weights & Biases and to Hugging Face hub if you want to push your model to the hub:
```
wandb login
huggingface-cli login
```

To fine-tune a model on this dataset you can use the following command:
