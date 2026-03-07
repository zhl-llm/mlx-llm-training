# mlx-llm-training

## Create virtual environment with pyenv

```sh
pyenv virtualenv 3.8.10 mlx-training-env
source ~/.pyenv/versions/mlx-training-env/bin/activate

pip install --upgrade pip
pip install "mlx-lm[train]" datasets
```

```sh
mlx_lm.lora --config configs/llama_lora_config.yaml

mlx_lm.lora --config configs/qwen_lora_config.yaml
```
