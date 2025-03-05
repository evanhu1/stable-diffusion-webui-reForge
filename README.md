# Stable Diffusion WebUI Forge/reForge

## Setup

For face id ip adaptor need lora ip-adapter-faceid-plusv2_sd15_lora.safetensors

```bash
wget https://huggingface.co/h94/IP-Adapter-FaceID/resolve/main/ip-adapter-faceid-plusv2_sd15_lora.safetensors?download=true -O ip-adapter-faceid-plusv2_sd15_lora.safetensors
```

For ControlNet need `control_v11p_sd15_scribble.pth` and `ip-adapter-faceid-plusv2_sd15.bin`

For Stable-diffusion need `helloyoung25d_V15jvae.safetensors` and `Realistic_Vision_V5.1_fp16-no-ema.safetensors`
```bash
wget https://huggingface.co/SG161222/Realistic_Vision_V5.1_noVAE/resolve/main/Realistic_Vision_V5.1_fp16-no-ema.safetensors?download=true -O RealisticVision5.safetensors
```

## Important: Branches
* evan: has controlnet fix, and customized for serving via api on linux with sudo root user.
