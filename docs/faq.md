# FAQ

### 1. How do I install the roop extension?
ttttttttttttttttttttt

While your pod is running and the Network Volume is attached:

#### Install the extension

```bash
source /workspace/venv/bin/activate
cd /workspace/stable-diffusion-webui/extensions
git clone --depth=1 https://github.com/ashleykleynhans/sd-webui-roop.git
cd /workspace/stable-diffusion-webui/extensions/sd-webui-roop
pip3 install -r requirements.txt
```

#### Download the model

```bash
mkdir -p /workspace/stable-diffusion-webui/models/roop
cd /workspace/stable-diffusion-webui/models/roop && \
wget https://huggingface.co/ashleykleynhans/inswapper/resolve/main/inswapper_128.onnx
```
