---
layout: default
---
# BabelPic

Welcome to the page of BabelPic, a project of the [Sapienza NLP Group](http://nlp.uniroma1.it), developed with the support of the awesome [MOUSSE ERC project](http://mousse-project.org/)!

## The BabelPic Dataset

BabelPic is a dataset targeting non-concrete concepts, built by cleaning the image-synset associations found within [BabelNet](https://babelnet.org/), a large multilingual encyclopedic dictionary. Our dataset was annotated manually and then extended using an automatic concept verification technique that exploits [VLP](https://github.com/LuoweiZhou/VLP).

To learn more, read our paper:

Agostina Calabrese, Michele Bevilacqua, and Roberto Navigli. 2020. [Fatality Killed the Cat or: BabelPic, a Multimodal Dataset for Non-Concrete Concepts.](https://www.aclweb.org/anthology/2020.acl-main.425/) *Proceedings of ACL*, pp. 4680-4686

## The EViLBERT Sense Embeddings
EViLBERT embeddings are multimodal sense embeddings, which encode jointly gloss and image features, using as data the image-synset pairs in BabelPic.

For more details, we invite you to read the paper:

Agostina Calabrese, Michele Bevilacqua, and Roberto Navigli. 2020. [EViLBERT: Learning Task-Agnostic Multimodal Sense Embeddings](https://www.ijcai.org/Proceedings/2020/67) *Proceedings of IJCAI*, pp. 481-487

## Download

We release our dataset as a`.tar.gz` archive containing the images in BabelPic. The filenames point to the corresponding BabelNet ids.

Download the **gold** BabelPic dataset at:
* GOLD: [`.tar.gz` (Google Drive)](https://drive.google.com/file/d/1pOsn2dlRaSAMjX-0x_Bj4MnSaXcHXOFs/view?usp=sharing)

Download the **silver** BabelPic dataset at:
* SILVER (split 0): [`.tar.gz` (Google Drive)](https://drive.google.com/file/d/16wmaAuvJUWALs-lN0Ao55UuvusZpWUen/view?usp=sharing)
* SILVER (split 1): [`.tar.gz` (Google Drive)](https://drive.google.com/file/d/1A-ZFUEbJz81GLmlpVsjnDyL2nmLZzdAq/view?usp=sharing)
* SILVER (split 2): [`.tar.gz` (Google Drive)](https://drive.google.com/file/d/10F3EXcgpioIg67IGw1joa_Cah5LiReQS/view?usp=sharing)
* SILVER (split 3): [`.tar.gz` (Google Drive)](https://drive.google.com/file/d/1UuCkKyK0TlcGWpRxweahMWQBeocJi03B/view?usp=sharing)

Download the **silver** extension produced for EViLBERT (which also contains concrete concepts):
* SILVER (split 4): [`.tar.gz` (Google Drive)](https://drive.google.com/file/d/1rQ3LGRx5jf3twPwOFYjyR3D7BGbofdOB/view?usp=sharing)
* SILVER (split 5): [`.tar.gz` (Google Drive)](https://drive.google.com/file/d/1RK2yyQclCRA_IFveqFFQjp_dDQqnmtdf/view?usp=sharing)
* SILVER (split 6): [`.tar.gz` (Google Drive)](https://drive.google.com/file/d/1yuc9FwMGJ_q9UW4Vy63jIXT7HqUO9CRK/view?usp=sharing)
* SILVER (split 7): [`.tar.gz` (Google Drive)](https://drive.google.com/file/d/1y3z9MNqYqUgrdRDctUDhj7QW87oDRkwe/view?usp=sharing)
* SILVER (split 8): [`.tar.gz` (Google Drive)](https://drive.google.com/file/d/1uU6weIq1gyU-egqHp5_1PqzHJpwRdf1z/view?usp=sharing)
* SILVER (split 9): [`.tar.gz` (Google Drive)](https://drive.google.com/file/d/1pTcr3GEI8NP5H_INot05l1DZ3DPd9FT0/view?usp=sharing)
* SILVER (split 10): [`.tar.gz` (Google Drive)](https://drive.google.com/file/d/1lEDTm-Y0CPx-DZe7NtEQxf5N-uHroXwL/view?usp=sharing)
* SILVER (split 11): [`.tar.gz` (Google Drive)](https://drive.google.com/file/d/1tWPqBiU3UIZSUFN8YA1M4BwDpZJLZsFt/view?usp=sharing)
* SILVER (split 12): [`.tar.gz` (Google Drive)](https://drive.google.com/file/d/1hOyaIR5NCjGxD_xet5K08XmcyuJdJ8SR/view?usp=sharing)
* SILVER (split 13): [`.tar.gz` (Google Drive)](https://drive.google.com/file/d/1o7SOerYuZlg0QOslgswFteAuxdT2kthq/view?usp=sharing)

Download EViLBERT multimodal embeddings:
* EViLBERT [plaintext `.vec` (Google Drive)](https://drive.google.com/file/d/16oiOcc76uTvXyDeX7Leqjbo1lc-Fc9zc/view?usp=sharing)

## Statistics

### BabelPic

|**Dataset**         | **Images** | **Synsets**|
|:--                 | --:        | --:        |
|Gold                |  14,931    |   2,733    |
|Silver [split 0-3]  |  65,497    |  10,013    |
|Silver [split 0-13] | 327,248    |  42,769    |

### EViLBERT

|**Embeddings**  | **Synsets** |
|:--             | --:         |
|EViLBERT        | 45,312      |

## Reference
If you use our data, please cite our papers:

### BabelPic

```
@inproceedings{calabrese-etal-2020-fatality,
    title = "Fatality Killed the Cat or: {B}abel{P}ic, a Multimodal Dataset for Non-Concrete Concepts",
    author = "Calabrese, Agostina  and
      Bevilacqua, Michele  and
      Navigli, Roberto",
    booktitle = "Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics",
    month = jul,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.acl-main.425",
    pages = "4680--4686",
}
```

### EViLBERT

```
@inproceedings{calabrese-etal-2020-evilbert,
  title     = "{EV}i{LBERT}: {L}earning Task-Agnostic Multimodal Sense Embeddings",
  author    = "Calabrese, Agostina and Bevilacqua, Michele and Navigli, Roberto",
  booktitle = "Proceedings of the Twenty-Ninth International Joint Conference on
               Artificial Intelligence, {IJCAI-20}",
  publisher = "International Joint Conferences on Artificial Intelligence Organization",             
  pages     = "481--487",
  year      = "2020",
  month     = "jul",
  url       = "https://doi.org/10.24963/ijcai.2020/67"
}
```

## Authors
             
<img src="https://sapienzanlp.github.io/babelpic/imgs/calabrese.jpg" width="150" height="150"> |  <img src="https://sapienzanlp.github.io/babelpic/imgs/bevilacqua.jpg" width="150" height="150"> | <img src="https://sapienzanlp.github.io/babelpic/imgs/navigli.jpg" width="150" height="150"> 
[Agostina Calabrese](https://ago3.github.io) | [Michele Bevilacqua](https://mbevila.github.io) | [Roberto Navigli](http://wwwusers.di.uniroma1.it/~navigli/)
[@agostina_cal](https://twitter.com/agostina_cal) | [@MicheleBevila20](https://twitter.com/MicheleBevila20) |[@rnavigli](https://twitter.com/rnavigli) 

## License
Both the BabelPic dataset and the EViLBERT embeddings are released under the CC-BY-NC 4.0 license.

## Acknowledgement
The authors gratefully acknowledge the support of the [ERC Consolidator Grant MOUSSE No. 726487](http://mousse-project.org/) under the European Union's Horizon 2020 research and innovation programme.
