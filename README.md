# KTV
The code of KTV: Keyframes and Key Tokens Selection for Efficient Training-Free Video LLMs, accepted by AAAI-2026
## setup
1. Clone this repository and navigate to LLaVA folder
```
git clone https://github.com/haotian-liu/LLaVA.git
cd LLaVA
```

2. Install Package
```
conda create -n ktv-llava python=3.10 -y
conda activate ktv-llava
pip install --upgrade pip  # enable PEP 660 support
pip install -e .
```
3.Download pre-trained LLaVA-NeXT weights from HuggingFace, and put them under the ktv folder.
```
git lfs clone https://huggingface.co/liuhaotian/llava-v1.6-vicuna-7b liuhaotian/llava-v1.6-vicuna-7b
git lfs clone https://huggingface.co/liuhaotian/llava-v1.6-34b liuhaotian/llava-v1.6-34b
```

## Acknowledgement
We build our project on awesome projects: [LLaVA](https://llava-vl.github.io/), [SF-LLaVA](https://github.com/apple/ml-slowfast-llava), [IG-VLM](https://github.com/imagegridworth/IG-VLM)
