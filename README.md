# Corona-mini-dataset

This is a tiny Turkish corpus consisting of comments about Corona symptoms. The corpus is compiled from two Ekşisözlük headlines "covid-19 belirtileri" and "gün gün koronavirüs belirtileri": 

https://eksisozluk.com/covid-19-belirtileri--6416646  

https://eksisozluk.com/gun-gun-koronavirus-belirtileri--6757665

This corpus 

- contains 178 raw, 175 processed comments
- all comments are in Turkish
- comes in 2 versions, raw and mildly processed.

For the processed version html tags, expressions in brackets and some other tags are removed.

This dataset is available on [Huggingface](https://huggingface.co/datasets/turkish-nlp-suite/Corona-mini) as well, you can use it as:

```
from datasets import load_dataset
dataset = load_dataset("turkish-nlp-suite/Corona-mini")
```

if you want more information about how this dataset is crafted you can watch the playlist [How to compile datasets](https://www.youtube.com/playlist?list=PLJTHlIwB8Vco4ONU_mCNOYIcVyFA9QrBr). For more Turkish NLP datasets, code and pretrained models you can either visit [fine Turkish NLP website](https://www.turkish-nlp-suite.com) or [my personal website](https://www.onlyduygu.com).

If you use this dataset in your own works, please kindly cite the ACL paper [A Diverse Set of Freely Available Linguistic Resources for Turkish](https://aclanthology.org/2023.acl-long.768/) :

```
@inproceedings{altinok-2023-diverse,
    title = "A Diverse Set of Freely Available Linguistic Resources for {T}urkish",
    author = "Altinok, Duygu",
    booktitle = "Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = jul,
    year = "2023",
    address = "Toronto, Canada",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.acl-long.768",
    pages = "13739--13750",
    abstract = "This study presents a diverse set of freely available linguistic resources for Turkish natural language processing, including corpora, pretrained models and education material. Although Turkish is spoken by a sizeable population of over 80 million people, Turkish linguistic resources for natural language processing remain scarce. In this study, we provide corpora to allow practitioners to build their own applications and pretrained models that would assist industry researchers in creating quick prototypes. The provided corpora include named entity recognition datasets of diverse genres, including Wikipedia articles and supplement products customer reviews. In addition, crawling e-commerce and movie reviews websites, we compiled several sentiment analysis datasets of different genres. Our linguistic resources for Turkish also include pretrained spaCy language models. To the best of our knowledge, our models are the first spaCy models trained for the Turkish language. Finally, we provide various types of education material, such as video tutorials and code examples, that can support the interested audience on practicing Turkish NLP. The advantages of our linguistic resources are three-fold: they are freely available, they are first of their kind, and they are easy to use in a broad range of implementations. Along with a thorough description of the resource creation process, we also explain the position of our resources in the Turkish NLP world.",
}
```


--------------

# Korona-mini veriseti

Yılın en berbat verisetinin reposuna hoş geldiniz😊 Bu ufak veriseti Korona belirtileriyle ilgili yorumları barındıran bir verisetidir, iki adet Ekşisözlük başlığından toplanmıştır.
Bu veriseti 

- 178 işlenmemiş, 175 işlenmiş yorum içermektedir.
- tüm yorumlar Türkçe'dir.
- işlenmiş ve az işlenmiş olarak 2 farklı formatta sunulmaktadır.

Az işlenmiş verisetini HTML taglerini, linkleri ve parantez içindeki bknz. türü ifadeleri çıkararak yaptım.
Bu verisetini isterseniz [Huggingface'den de](https://huggingface.co/datasets/turkish-nlp-suite/Corona-mini) indirebilirsiniz:

```
from datasets import load_dataset

dataset = load_dataset("turkish-nlp-suite/Corona-mini")
```

Bu verisetini nasıl derlediğimi öğrenmek isterseniz, [Veriseti nasıl derlenir?](https://www.youtube.com/playlist?list=PLJTHlIwB8Vco4ONU_mCNOYIcVyFA9QrBr) video serisini izleyebilirsiniz.
Daha fazla Türkçe veriseti, model ve kod için [Türkçe NLP sitemi](https://www.turkish-nlp-suite.com) veya [bireysel sitemi](https://www.onlyduygu.com) ziyaret edebilirsiniz. 


--------------

This work is supported by Google Developer Experts Program.

Part of Duygu 2022 Fall-Winter collection, "Turkish NLP with Duygu"/ "Duygu'yla Türkçe NLP". All rights reserved.



Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
