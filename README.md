# sample-generator
Tools to train a generative model on arbitrary audio samples

**This fork adds inpainting using the [RePaint](https://arxiv.org/pdf/2201.09865.pdf) method and [Diffusion Posterior Sampling](https://arxiv.org/pdf/2209.14687.pdf)**

Dance Diffusion notebook (Inpainting via RePaint): [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/realfolkcode/sample-generator/blob/main/Dance_Diffusion_Inpainting.ipynb)

Dance Diffusion notebook (Inpainting via Posterior Sampling): [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/realfolkcode/sample-generator/blob/main/Dance_Diffusion_Inpainting_Posterior.ipynb)

Dance Diffusion fine-tune notebook: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Harmonai-org/sample-generator/blob/main/Finetune_Dance_Diffusion.ipynb)

## Prerequisites
Dance Diffusion requires Python 3.7+

You can install the required packages by running `pip install .` from the root of the repo

## Todo

- [x] Add inference notebook
- [x] Add interpolations to nobebook
- [x] Add fine-tune notebook
- [ ] Add guidance to notebook
