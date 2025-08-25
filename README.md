# Imaginaire-I2I
### [Docs](http://deepimagination.cc/) | [License](LICENSE.md) | [Installation](INSTALL.md) | [Model Zoo](MODELZOO.md)

Imaginaire is a [pytorch](https://pytorch.org/) library that contains
optimized implementation of several image and video synthesis methods developed at [NVIDIA](https://www.nvidia.com/en-us/).

## What to Do?
We have a plan to add all the image-to-image translation models.

### Supervised Image-to-Image Translation

|Algorithm Name                               | Feature                                                                                                         | Publication                                                   |
|:--------------------------------------------|:----------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------:|
|[pix2pixHD](projects/pix2pixhd/README.md)     | Learn a mapping that converts a semantic image to a high-resolution photorealistic image.                       |    [Wang et. al. CVPR 2018](https://arxiv.org/abs/1711.11585) |
|[SPADE](projects/spade/README.md)             | Improve pix2pixHD on handling diverse input labels and delivering better output quality.                        |    [Park et. al. CVPR 2019](https://arxiv.org/abs/1903.07291) |


### Unsupervised Image-to-Image Translation


|Algorithm Name                               | Feature                                                                                                         | Publication                                                   |
|:--------------------------------------------|:----------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------:|
|[UNIT](projects/unit/README.md)               | Learn a one-to-one mapping between two visual domains.                                                          |    [Liu et. al. NeurIPS 2017](https://arxiv.org/abs/1703.00848) |
|[MUNIT](projects/munit/README.md)             | Learn a many-to-many mapping between two visual domains.                                                        |    [Huang et. al. ECCV 2018](https://arxiv.org/abs/1804.04732) |
|[FUNIT](projects/funit/README.md)             | Learn a style-guided image translation model that can generate translations in unseen domains.                  |    [Liu et. al. ICCV 2019](https://arxiv.org/abs/1905.01723) |
|[COCO-FUNIT](projects/coco_funit/README.md)   | Improve FUNIT with a content-conditioned style encoding scheme for style code computation.                      |    [Saito et. al. ECCV 2020](https://arxiv.org/abs/2007.07431) |

## License

Imaginaire is released under [NVIDIA Software license](LICENSE.md).
For commercial use, please consult [NVIDIA Research Inquiries](https://www.nvidia.com/en-us/research/inquiries/).
