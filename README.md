# Additional reference translations for the English-to-German [WMT](http://www.statmt.org/wmt19/) test set nestest2018, newstest2019 and newstest2020.

The contents of this repository are not an official Google product.

[Additional References]
The sentences below are alternative reference translations for the WMT newstest20XX English-German test sets, produced through human translation or human paraphrasing. Automatic metrics like BLEU have been demonstrated to correlate better with human judgement when using these references than when using standard references. For details on data collection and how paraphrased references can improve the automatic evaluation of machine translation, see our paper below. Also, consider citing the paper if you are using this data for your research.
Currently the repo contains additional references for newstes2018, newstest2019 and newstest2020:

1. [newstest2018 WMT.p](wmt18/ende/wmt18-ende-wmtp.ref) A paraphrased as-much-as-possible version of the original WMT reference.

2. [newstest2019 AR](wmt19/ende/wmt19-ende-ar.ref) An additional high quality reference translation.

3. [newstest2019 AR.p](wmt19/ende/wmt19-ende-arp.ref) A paraphrased as-much-as-possible version of AR.

4. [newstest2019 WMT.p](wmt19/ende/wmt19-ende-wmtp.ref) A paraphrased as-much-as-possible version of the original WMT reference.

5. [newstest2019 HQ(R)](wmt19/ende/wmt19-ende-hqr.ref) A combined reference from the original reference translation and AR. Per sentence, humans picked one of the two reference translations.

6. [newstest2019 HQ(P)](wmt19/ende/wmt19-ende-hqp.ref) A combined reference from WMT.p and AR.p. Per sentence, humans picked one of the two reference translations.

7. [newstest2019 HQ(all)](wmt19/ende/wmt19-ende-hqall.ref) A combined reference from WMT, AR, WMT.p, AR.p. Per sentence, humans picked one of the two reference translations.

8. [newstest2020 WMT.p](wmt20/ende/wmt20-ende-wmtp.ref) A paraphrased as-much-as-possible version of the original WMT reference.

[Research Paper]

[BLEU might be Guilty but References are not Innocent](https://arxiv.org/abs/2004.06063)
Markus Freitag, David Grangier, Isaac Caswell - EMNLP 2020.

@inproceedings{freitag-bleu-paraphrase-references-2020,   
    title={BLEU might be Guilty but References are not Innocent},   
    author={Markus Freitag and David Grangier and Isaac Caswell},   
    booktitle = "Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP)",   
    year={2020},   
    month={nov},   
    url={https://arxiv.org/abs/2004.06063}
}
