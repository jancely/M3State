# M3State

The repo is the official implementation for the paper: [M3State:  Mamba-Enhanced Multiscale State Space Selection for Multivariate Time Series Forecasting].
The code will released immediatly when the work is accepted.


## Installation 

1. Install Pytorch and necessary dependencies.

```
pip install -r requirements.txt
```

## Training Example
Train and evaluate the model. We provide all the above tasks under the folder ./scripts/. You can reproduce the results as the following examples:

```
# Multivariate forecasting with ARCausal
bash ./scripts/M3State_ETTh1.sh
bash ./scripts/M3State_ETTh2.sh
bash ./scripts/M3State_ETTm1.sh
bash ./scripts/M3State_ETTm2.sh
bash ./scripts/M3State_ECL.sh
bash ./scripts/M3State_WTH.sh
bash ./scripts/M3State_Solar.sh
bash ./scripts/M3State_Exchange.sh
bash ./scripts/M3State_PEMS03.sh
bash ./scripts/M3State_PEMS04.sh
bash ./scripts/M3State_PEMS07.sh
bash ./scripts/M3State_PEMS08.sh
```

## Main Result of Multivariate Forecasting

We evaluate the M3State on challenging multivariate forecasting benchmarks (**generally hundreds of variates**). **Comprehensive good performance** (MSE/MAE) is achieved.


## Acknowledgement

We appreciate the following GitHub repos a lot for their valuable code and efforts.
- iTransformer (https://github.com/thuml/iTransformer)
- Causal-TSF (https://github.com/AKAGB/Causal-TSF)
- Mamba (https://github.com/state-spaces/mamba)
- Crossformer (https://github.com/Thinklab-SJTU/Crossformer)
- PatchTST (https://github.com/yuqinie98/PatchTST)
- MSGNet (https://github.com/YoZhibo/MSGNet)
- DLinear (https://github.com/ioannislivieris/DLinear)
- TimeMixer (https://github.com/kwuking/TimeMixer)
- Time-Series-Library (https://github.com/thuml/Time-Series-Library)

This work was supported in part by  the Science and Technology Talents and Platform Plan: Technology Innovation Center of Yunnan Province for Digital Water Engineering under Grant 202305AK34003, in part by the Yunnan Zhang Zongliang Scientist Studio under Grant 2021KXJGZS01 and in part by Yunnan Fundamental Research Projects under Grant 202401AT070471.

## Contact

If you have any questions or want to use the code, feel free to contact:
* Chengli Zhou (chenglizhou@mail.ynu.edu.cn)
* Chunna Zhao (zhaochunna@ynu.edu.cn)
