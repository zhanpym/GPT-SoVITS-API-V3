# GPT-SoVITS-API-V3
Fix some bugs related to API-V3.

Original GPT-SoVITS link: https://github.com/RVC-Boss/GPT-SoVITS

1. Place `api_v3.py` directly in the main directory, and replace the original `config.py` with the new one.
2. Download the weights for v3 from https://huggingface.co/lj1995/GPT-SoVITS/tree/main, and place them at `"GPT_SoVITS/pretrained_models/s2Gv3.pth"` and `"GPT_SoVITS/pretrained_models/s1v3.ckpt"`.
3. Run the program using `python api_v3.py`. By default, it runs on port 9880. You can also specify a port using `-p`. 
