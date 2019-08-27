# Dataset_for_Multisense
This repository is the "Dataset Based on Concept Hierarchy for Evaluating Word Vectors Learned from Multisense Words".

Our approch enables us to make the dataset automatically (in this experiment, we remove a part of selected words by hand because some words have sexual meanings) and this approch can evaluate word vectors that consider multisense words (MSSG, DeConf, and so on) properly.
Of course, concept hierarchies are needed to maintain by hand, so constructing a concept hierarchy that has correctness and comprehension is very important for us. And, we say Thank You to people who maintain them.

## Our paper
Our paper is [here](https://link.springer.com/chapter/10.1007/978-3-030-30639-7_8) and our citation is following.
```
@InProceedings{10.1007/978-3-030-30639-7_8,
author="Yamazaki, Tomoaki
and Toyota, Tetsuya
and Ohara, Kouzou",
title="Constructing Dataset Based on Concept Hierarchy for Evaluating Word Vectors Learned from Multisense Words",
booktitle="Knowledge Management and Acquisition for Intelligent Systems",
year="2019",
publisher="Springer International Publishing",
address="c5618168@aoyama.jp",
pages="81--96",
}
```

# Future Work
This paper provides 
Our future works are divided into 2 types of strategies:
one is the validity of this proposed dataset because we need to investigate this dataset in a various setting, and the other one is the extension to sentence-based dataset to evaluate word vectors that have the probability to change words' meaning.
This proposed dataset evaluates word vecotrs directly; maybe it's should be called sense-based evaluation (We call word similarity datasets word-based evaluation because they evaluate word vectors by using similarities between words).
Sentence-based evaluation evaluates word vectors in sentences such as CoVe, ELMo, and so on.

# Schedule of Publication
- until 15/09/2019, we will publish the dataset and evaluation codes.
- until 31/03/2020 (I aim until 2019), we will publish the next paper about the detail of this proposed construction methods and evaluation metric.
- while 2020 (I aim until 31/03/2020), we might be going to publish the paper about sentence-based evaluation.
