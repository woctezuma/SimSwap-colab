# SimSwap-Colab

The goal of this repository is to provide a Colab notebook to apply SimSwap [1] to images.

# Usage

-   Run [`SimSwap_images.ipynb`][colab-notebook-simswap-images] to apply SimSwap to images.
[![Open In Colab][colab-badge]][colab-notebook-simswap-images]

-   Run [`gpen/SimSwap_images.ipynb`][colab-notebook-simswap-images-gpen] to apply SimSwap and GPEN [2] to images.
[![Open In Colab][colab-badge]][colab-notebook-simswap-images-gpen]

-   Run [`SimSwap_videos.ipynb`][colab-notebook-simswap-videos] to apply SimSwap to GIF images/videos.
[![Open In Colab][colab-badge]][colab-notebook-simswap-videos]

# Results

<img alt="Image source" src="https://github.com/woctezuma/SimSwap-colab/wiki/img/source.jpg" width="250"> + <img alt="Image target" src="https://github.com/woctezuma/SimSwap-colab/wiki/img/destination.jpg" width="250"> = <img alt="Output of SimSwap" src="https://github.com/woctezuma/SimSwap-colab/wiki/img/cover-banner.jpg" width="250">

<sub>
Face swapping with a source (left) and a target image (middle). The result is on the right.
</sub>

---

<img alt="Alan Wake feat. Tim Sweeney" src="https://github.com/woctezuma/SimSwap-colab/wiki/img/alan_wake.jpg" height="350"><img alt="EGS meme feat. Tim Sweeney" src="https://github.com/woctezuma/SimSwap-colab/wiki/img/egs_meme.jpg" height="350">

<sub>
Different results obtained with the face of Tim Sweeney, founder and creator of Epic Games. Left: video game Alan Wake. Right: meme about Epic Games store.
</sub>

# References

[1] Chen, Renwang, et al. *SimSwap: An Efficient Framework For High Fidelity Face Swapping*. In Proceedings of the 28th ACM International Conference on Multimedia. 2020.
([code][simswap-code] and [paper][simswap-paper])

[2] Yang, Tao, et al. *GAN Prior Embedded Network for Blind Face Restoration in the Wild*. arXiv preprint arXiv:2105.06070. 2021.
([code][gpen-code] and [paper][gpen-paper])

[img-source]: <https://github.com/woctezuma/SimSwap-colab/wiki/img/source.jpg>
[img-target]: <https://github.com/woctezuma/SimSwap-colab/wiki/img/destination.jpg>
[cover-banner]: <https://github.com/woctezuma/SimSwap-colab/wiki/img/cover-banner.jpg>

[colab-notebook-simswap-images]: <https://colab.research.google.com/github/woctezuma/SimSwap-colab/blob/main/SimSwap_images.ipynb>
[colab-notebook-simswap-images-gpen]: <https://colab.research.google.com/github/woctezuma/SimSwap-colab/blob/gpen/SimSwap_images.ipynb>
[colab-notebook-simswap-videos]: <https://colab.research.google.com/github/woctezuma/SimSwap-colab/blob/main/SimSwap_videos.ipynb>
[colab-badge]: <https://colab.research.google.com/assets/colab-badge.svg>

[simswap-code]: <https://github.com/neuralchen/SimSwap>
[simswap-paper]: <https://arxiv.org/abs/2106.06340v1>

[gpen-code]: <https://github.com/yangxy/GPEN>
[gpen-paper]: <https://arxiv.org/abs/2105.06070>
