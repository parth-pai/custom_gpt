# custom_gpt

GPT on Shakespeare's text 

This repository contains an input.txt file containing the Shakespeare text and custom_nanoGPT.ipynb file where the self-attention block is hardcoded to generate the Shakespeare text. One can look at the code for the values used for hyperparameters and the hyperparameter_explain.pdf for intuitive understanding of the same. It took me about ~ 32 minutes to train the model in the T4 GPU of Google Colab. The training will get faster if the NVIDIA A100 GPU is used. 

These are the resources I referred to for the repository:
1) Attention is All you need: https://arxiv.org/abs/1706.03762
2) Language Models are Few-Shot Learners (GPT 3 paper): https://arxiv.org/abs/2005.14165
3) Deep Residual Learning for Image Recognition (for residual learning): https://arxiv.org/abs/1512.03385
