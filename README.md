# LLM4ED


> The implementation and data of the paper: [**Harnessing the Power of Large Language Models for Empathetic Response Generation: Empirical Investigations and Improvement**](https://arxiv.org/abs/2310.05140).


## Requirements

+ `torch`
+ `nltk`
+ `transformers`
+ `spacy`
+ `sentence-transformers`

## Preparation

+ Download the [COMET-BART checkpoint](https://storage.googleapis.com/ai2-mosaic-public/projects/mosaic-kgs/comet-atomic_2020_BART.zip) and place it in `data/Comet`.

## Usage

```
bash main.sh
```

## Proposal
The data from this work is available [here](https://drive.google.com/drive/folders/1avXluZqbVy6nky6mYrcfTDFOZ8wxjBIg?usp=drive_link).  
You can leverage the data generated by powerful LLMs (e.g., ChatGPT) to empower other LLMs.


## Citation

If our work is useful for your research, please kindly cite our paper as follows:

```
@article{qian2023harnessing,
      title={Harnessing the Power of Large Language Models for Empathetic Response Generation: Empirical Investigations and Improvements},
      author={Qian, Yushan and Zhang, Wei-Nan and Liu, Ting},
      journal={arXiv preprint arXiv:2310.05140},
      year={2023},
}
```
