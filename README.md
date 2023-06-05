# Factual Generalization Capabilities of GPT-3 Across Domains

This repository presents the course project for DS-UA 203 Machine Learning for Language Understanding (Spring 2022), mainly using Python. This course is an equivalent for CSCI-UA 480 Natural Language Processing.

GPT-3 has achieved impressive results in general purpose question answering tasks, exceeding human performance in some instances (Joshi et al., 2017), but still has its weaknesses. TruthfulQA (Lin et al., 2021) looks at imitative falsehoods stemming from defections in the training dataset, and provides a benchmark of questions where the most common answer online will likely be false. Building on this, we present a further study on generalizing factuality across domains where such falsehoods are prone. We evaluate the effectiveness of different domain combinations and prompting techniques after cross-prompting among six domains. Further exploration of the generalization capacities beyond questions present in TruthfulQA is then provided.

- Read [full report](https://github.com/koapushjin/Spring2022-NLP-project/blob/main/nlp_report.pdf) here
- [aqa_v1](https://github.com/koapushjin/Spring2022-NLP-project/tree/main/aqa_v1): contains AdvasarialQA
- [initial attempts](https://github.com/koapushjin/Spring2022-NLP-project/tree/main/initial%20attempts): contains basic experiments
- [Plots](https://github.com/koapushjin/Spring2022-NLP-project/tree/main/Plots): contains all plots included in our research paper
- [TruthfulQA-main](https://github.com/koapushjin/Spring2022-NLP-project/tree/main/TruthfulQA-main): TruthfulQA
- [trivial_train1](https://github.com/koapushjin/Spring2022-NLP-project/blob/main/trivial_train1.numbers), [trivial_verified](https://github.com/koapushjin/Spring2022-NLP-project/blob/main/trivial_verified.numbers): TriviaQA after preprocessed
- [experiments](https://github.com/koapushjin/Spring2022-NLP-project/tree/main/experiments): experiment logs
- [codes](https://github.com/koapushjin/Spring2022-NLP-project/tree/main/codes): all relevant codes
- [results](https://github.com/koapushjin/Spring2022-NLP-project/tree/main/results): contain the result CSVs for all experiments

Group Member: Tian Jin, Muyang Xu, Dennis Hu
