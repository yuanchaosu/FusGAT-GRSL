# FusGAT-GRSL
demo of FusGAT
Code for the paper:FusGAT: Graph Attention-Based Fusion Network for Unsupervised Hyperspectral Image Super-Resolution


## How to run our code
- Parameters: All the parameters that need fine-tuning can be found in `config.py`.

- Data: If you use simulated data, put your HSI data and MSI spectral reponse in `./data/**` and `./data/spectral_response/**.xls`, respectively. If you use real data, put your HSI data MSI data `./data/**`.
TianGong-1 data (simulated data) is used as references.

- Run: Just simply run `main.py` after adjusting the parameters in `config.py`.

- Results: Saved in checkpoint

If you don't have a proper runtime environment yet, we've uploaded one that's already been tuned.

Python environment:
https://drive.google.com/file/d/1fO3ecdIlrm2efFHZkCNHtXxVvbWz7a_G/view?usp=drive_link

Data download:
https://github.com/yuanchaosu/TGRS-daan

### Contact
If you happen to encounter any bugs while using this code, please do not hesitate to contact us.

JinXu (JinXu0615@163.com).
Yuanchao Su (suych@um.edu.mo)
