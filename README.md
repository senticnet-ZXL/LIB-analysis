# LIB-analysis

This repository contains the LIB-based bias analysis methods proposed in [Tell-tale Signs of Implicit Bias: Language Abstraction for Automated Bias Analysis](https://escholarship.org/content/qt9h19z7ft/qt9h19z7ft.pdf), and [Implicit Bias in Peer Review: Through the Lens of Language Abstraction](https://aclanthology.org/2026.lrec-1.752.pdf). 

## Usage
To use the abstraction scoring regression model proposed in [Implicit Bias in Peer Review: Through the Lens of Language Abstraction](https://aclanthology.org/2026.lrec-1.752.pdf), run the `abstract_scoring_peer_review.ipynb` jupyter notebook file. The data used for training and the experiments can be found from sources listed in the paper.

To use the abstraction span extraction model proposed in [Tell-tale Signs of Implicit Bias: Language Abstraction for Automated Bias Analysis](https://escholarship.org/content/qt9h19z7ft/qt9h19z7ft.pdf), run the `abstract_instruct_span_exaction.ipynb`file on Kaggle notebook after acquiring access of the LLAMA-instruct model via Kaggle. The finetuning dataset is listed in the repository as `wsj_data_300.json`. The processed datasets used for experiments can be found in [intergroup](https://www.kaggle.com/datasets/xulangzhang/intergroup) and [POLUSA](https://www.kaggle.com/datasets/xulangzhang/polusa).

## Citation
If you use the abstraction scoring regression model, please cite the paper - [Implicit Bias in Peer Review: Through the Lens of Language Abstraction](https://aclanthology.org/2026.lrec-1.752.pdf) with the following:
```
@inproceedings{DBLP:conf/lrec/ZhangMC26,
  author       = {Xulang Zhang and
                  Rui Mao and
                  Erik Cambria},
  editor       = {Stelios Piperidis and
                  N{\'{u}}ria Bel and
                  Henk van den Heuvel and
                  Nancy Ide and
                  Simon Krek and
                  Antonio Toral},
  title        = {Implicit Bias in Peer Review: Through the Lens of Language Abstraction},
  booktitle    = {Proceedings of the Fifteenth Language Resources and Evaluation Conference,
                  {LREC} 2026, Palma de Mallorca, Spain, May 13-15, 2026},
  pages        = {9569--9580},
  publisher    = {{ELRA} Language Resource Association / {ACL}},
  year         = {2026},
  url          = {https://doi.org/10.63317/4uxwwzgswmqc},
  doi          = {10.63317/4UXWWZGSWMQC},
  timestamp    = {Tue, 11 Aug 2026 16:59:37 +0200},
  biburl       = {https://dblp.org/rec/conf/lrec/ZhangMC26.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}
```

If you use the abstraction span extraction model, please cite the paper - [Tell-tale Signs of Implicit Bias: Language Abstraction for Automated Bias Analysis](https://escholarship.org/content/qt9h19z7ft/qt9h19z7ft.pdf) with the following:
```
@inproceedings{zhang2026tell,
  title={Tell-tale Signs of Implicit Bias: Language Abstraction for Automated Bias Analysis},
  author={Zhang, Xulang and Mao, Rui and Ge, Mengshi and Cambria, Erik},
  booktitle={Proceedings of the Annual Meeting of the Cognitive Science Society},
  volume={48},
  year={2026}
}
```
