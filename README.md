<<<<<<< HEAD
# PCA-Guided Autoencoding
## PCA-Guided Autoencoding for Structured Dimensionality Reduction in Active Infrared Thermography

#
You can find the PDF of the paper [here]().
If you use this code in an academic context please cite this publication:

```bibtex
@misc{pca_guided_ae,
      title={PCA-Guided Autoencoding for Structured Dimensionality Reduction in Active Infrared Thermography}, 
      author={Yusra Abdulrahman and Mohammed Salah and Numan Saeed and Davor Svetinovic and Mohammed Omar},
      year={2025},
      eprint={},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={}, 
}
```

## Supported platforms

Tested on the following platforms:

- Ubuntu 18.04 and 20.04 LTS

## Prerequisites
You can test the framework on the IRT-PVC dataset available in:
[Dataset](https://www.kaggle.com/datasets/ziangwei/irtpvc)

## Running the code
### Step 1: Create a conda environment
Create pca_guided_ae conda environment:
```
git clone https://github.com/mohammedsalah98/pca_guided_ae.git
cd pca_guided_ae
conda env create -f environment.yml
conda activate pca_guided_ae
```

### Step 2: Running the code:
```
apply_tsr.ipynb --> Applies thermographic signal reconstruction
apply_pca.ipynb --> Applies principal component analysis
apply_cnn.ipynb --> Applies 1D-DCAE-AIRT
apply_ae.ipynb --> Applies a fully connected autoencoder without PCA distillation loss - DAT
apply_ae_kd.ipynb --> Applies a fully connected autoencoder with PCA distillation loss
```
=======
# pca_guided_ae
PCA-Guided Autoencoding for Dimensionality Reduction
>>>>>>> e4f730f013d513a5bb3a01ce1e17153a87086a16
