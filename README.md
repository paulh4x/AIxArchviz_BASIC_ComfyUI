# ✨ PH's Basic ComfyUI ✨
## 🚀 for Archviz x AI Workflow Series (SDXL + Flux) 🚀
### v0.30_250630, <a href="https://github.com/paulh4x/AIxArchviz_BASIC_ComfyUI">PH's Basic ComfyUI</a> © 2025 by <a href="https://www.linkedin.com/in/paul-hansen-410695b6/">Paul Hansen</a> is licensed under <a href="https://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA 4.0</a><img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/sa.svg" style="max-width: 1em;max-height:1em;margin-left: .2em;">

---

### 💖 Support My Work
If you want to support my work and can afford it, you can donate directly at [https://ko-fi.com/paulhansen](https://ko-fi.com/paulhansen). Feel free to contribute your own enhancements based on this work to the open-source community (with credits), follow my socials, and/or share some content.

* 🌐 **Web**:		[https://www.paulhansen.de](https://www.paulhansen.de)
* 📸 **Instagram**:	[https://www.instagram.com/paulhansen.design/](https://www.instagram.com/paulhansen.design/)
* 🎥 **YouTube**:	[https://www.youtube.com/@Paul_Hansen](https://www.youtube.com/@Paul_Hansen)
* 💼 **LinkedIn**:	[https://www.linkedin.com/in/paul-hansen-410695b6/](https://www.linkedin.com/in/paul-hansen-410695b6/)
* 💬 **Discord**:	[https://discord.gg/QarZjskQmM](https://discord.gg/QarZjskQmM)

---

### 🎥 Video Tutorial

<a href="https://www.youtube.com/watch?v=1GcG9ySj4ME&list=PLp6RqZwhm0sqHsX-HnKyZ_5shrCu-_xxo&index=2&ab_channel=PaulHansen" target="_blank"><img src="https://img.youtube.com/vi/1GcG9ySj4ME/0.jpg" alt="Watch the video" width="480" height="360" border="10" /></a>

## 🛠️ Nodes and Models

Here are the nodes and models used throughout the entire workflow series.

### 🧩 Nodes
*   **KJNodes**: [https://github.com/kijai/ComfyUI-KJNodes](https://github.com/kijai/ComfyUI-KJNodes)
*   **SAM2**: [https://github.com/kijai/ComfyUI-segment-anything-2](https://github.com/kijai/ComfyUI-segment-anything-2)
*   **Florence2**: [https://github.com/kijai/ComfyUI-Florence2](https://github.com/kijai/ComfyUI-Florence2)
*   **rgthree**: [https://github.com/rgthree/rgthree-comfy](https://github.com/rgthree/rgthree-comfy)
*   **essentials**: [https://github.com/cubiq/ComfyUI_essentials](https://github.com/cubiq/ComfyUI_essentials)
*   **COG**: [https://github.com/kijai/ComfyUI-CogVideoXWrapper](https://github.com/kijai/ComfyUI-CogVideoXWrapper)
*   **HunYUAN3dwrapper**: [https://github.com/kijai/ComfyUI-Hunyuan3DWrapper](https://github.com/kijai/ComfyUI-Hunyuan3DWrapper)
*   **CustomScripts**: [https://github.com/pythongosssss/ComfyUI-Custom-Scripts](https://github.com/pythongosssss/ComfyUI-Custom-Scripts)
*   **IPAdapter_plus**: [https://github.com/cubiq/ComfyUI_IPAdapter_plus](https://github.com/cubiq/ComfyUI_IPAdapter_plus)
*   **Logic**: [https://github.com/theUpsider/ComfyUI-Logic](https://github.com/theUpsider/ComfyUI-Logic)
*   **AlekPet**: [https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
*   **Enricos**: [https://github.com/erosDiffusion/ComfyUI-enricos-nodes](https://github.com/erosDiffusion/ComfyUI-enricos-nodes)
*   **comfyui_ControlNet_aux**: [https://github.com/Fannovel16/comfyui_controlnet_aux](https://github.com/Fannovel16/comfyui_controlnet_aux)
*   **masquerade**: [https://github.com/BadCafeCode/masquerade-nodes-comfyui](https://github.com/BadCafeCode/masquerade-nodes-comfyui)
*   **efficency**: [https://github.com/jags111/efficiency-nodes-comfyui](https://github.com/jags111/efficiency-nodes-comfyui)
*   **ultimatesdupscale**: [https://github.com/ssitu/ComfyUI_UltimateSDUpscale](https://github.com/ssitu/ComfyUI_UltimateSDUpscale)
*   **videohelpersuite**: [https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite)
*   **WAS Suite**: [https://github.com/WASasquatch/was-node-suite-comfyui](https://github.com/WASasquatch/was-node-suite-comfyui)

### 📦 Models

#### ⚡ FLUX
| Model                 | Download Link                                                                                             | Installation Path        |
| --------------------- | --------------------------------------------------------------------------------------------------------- | ------------------------ |
| Flux1.dev             | [flux1-dev.safetensors](https://huggingface.co/black-forest-labs/FLUX.1-dev/resolve/main/flux1-dev.safetensors) | `/ComfyUI/models/unet/`    |
| t5xxl_fp16            | [t5xxl_fp16.safetensors](https://huggingface.co/comfyanonymous/flux_text_encoders/resolve/main/t5xxl_fp16.safetensors) | `/ComfyUI/models/clip/`    |
| clip_l                | [clip_l.safetensors](https://huggingface.co/comfyanonymous/flux_text_encoders/resolve/main/clip_l.safetensors) | `/ComfyUI/models/clip/`    |
| vae                   | [ae.safetensors](https://huggingface.co/black-forest-labs/FLUX.1-dev/resolve/main/ae.safetensors)             | `/ComfyUI/models/vae/`     |
| Flux.1-Fill-Dev       | [flux1-fill-dev.safetensors](https://huggingface.co/black-forest-labs/FLUX.1-Fill-dev/resolve/main/flux1-fill-dev.safetensors) | `/ComfyUI/models/unet/`    |
| Flux.1-Redux-Dev      | [flux1-redux-dev.safetensors](https://huggingface.co/black-forest-labs/FLUX.1-Redux-dev/resolve/main/flux1-redux-dev.safetensors) | `/ComfyUI/models/style_models/` |
| Flux.1-Depth-Dev-Lora | [flux1-depth-dev-lora.safetensors](https://huggingface.co/black-forest-labs/FLUX.1-Depth-dev-lora/resolve/main/flux1-depth-dev-lora.safetensors) | `/ComfyUI/models/loras/`   |
| Flux.1-Canny-Dev-Lora | [flux1-canny-dev-lora.safetensors](https://huggingface.co/black-forest-labs/FLUX.1-Canny-dev-lora/resolve/main/flux1-canny-dev-lora.safetensors) | `/ComfyUI/models/loras/`   |
| Clip Vision           | [sigclip_vision_patch14_384.safetensors](https://huggingface.co/Comfy-Org/sigclip_vision_384/resolve/main/sigclip_vision_patch14_384.safetensors) | `/ComfyUI/models/clip_vision/` |
| Flux.1-schnell-fp8    | [flux1-schnell-fp8.safetensors](https://huggingface.co/Comfy-Org/flux1-schnell/resolve/main/flux1-schnell-fp8.safetensors) | `/ComfyUI/models/checkpoints/` |
| Flux.1-Dev-Q8         | [flux1-dev-Q8_0.gguf](https://huggingface.co/city96/FLUX.1-dev-gguf/resolve/main/flux1-dev-Q8_0.gguf)         | `/ComfyUI/models/unet/`    |
| Flux.1-Dev-Q8 Clip    | [t5-v1_1-xxl-encoder-Q8_0.gguf](https://huggingface.co/city96/t5-v1_1-xxl-encoder-gguf/resolve/main/t5-v1_1-xxl-encoder-Q8_0.gguf) | `/ComfyUI/models/clip/`    |
| Controlnet UnionPro 2.0 | [diffusion_pytorch_model.safetensors](https://huggingface.co/Shakker-Labs/FLUX.1-dev-ControlNet-Union-Pro/resolve/main/diffusion_pytorch_model.safetensors) | `/ComfyUI/models/controlnet/` |

#### 🎨 SDXL
| Model                      | Download Link                                                                                               | Installation Path          |
| -------------------------- | ----------------------------------------------------------------------------------------------------------- | -------------------------- |
| RealVisXL_V4.0             | [RealVisXL_V4.0.safetensors](https://huggingface.co/SG161222/RealVisXL_V4.0/resolve/main/RealVisXL_V4.0.safetensors) | `/ComfyUI/models/checkpoints/` |
| RealvisXL_V3.0_INPAINTING  | [Download](https://civitai.com/api/download/models/297320)                                                  | `/ComfyUI/models/checkpoints/` |
| #Juggernaut XI             | [Juggernaut-XI-byRunDiffusion.safetensors](https://huggingface.co/RunDiffusion/Juggernaut-XI-v11/resolve/main/Juggernaut-XI-byRunDiffusion.safetensors) | `/ComfyUI/models/checkpoints/` |
| Clip Vision                | [open_clip_model.safetensors](https://huggingface.co/laion/CLIP-ViT-H-14-laion2B-s32B-b79K/resolve/main/open_clip_model.safetensors) | `/ComfyUI/models/clip_vision/` |
| ip-adapter_sdxl_vit-h      | [ip-adapter-plus_sdxl_vit-h.safetensors](https://huggingface.co/h94/IP-Adapter/resolve/main/sdxl_models/ip-adapter-plus_sdxl_vit-h.safetensors) | `/ComfyUI/models/ipadapter/`   |
| Controlnet Canny           | [diffusers_xl_canny_full.safetensors](https://huggingface.co/lllyasviel/sd_control_collection/resolve/main/diffusers_xl_canny_full.safetensors) | `/ComfyUI/models/controlnet/`  |
| Controlnet Depth           | [diffusers_xl_depth_full.safetensors](https://huggingface.co/lllyasviel/sd_control_collection/resolve/main/diffusers_xl_depth_full.safetensors) | `/ComfyUI/models/controlnet/`  |
| Controlnet OpenPose        | [thibaud_xl_openpose.safetensors](https://huggingface.co/lllyasviel/sd_control_collection/resolve/main/thibaud_xl_openpose.safetensors) | `/ComfyUI/models/controlnet/`  |

#### ➕ ADDITIONAL
| Model              | Download Link                                                                                             | Installation Path      |
| ------------------ | --------------------------------------------------------------------------------------------------------- | ---------------------- |
| SAM2               | [sam2.1_hiera_base_plus-fp16.safetensors](https://huggingface.co/Kijai/sam2-safetensors/resolve/main/sam2.1_hiera_base_plus-fp16.safetensors) | `/ComfyUI/models/sam2/`  |
| Florence2 Large    | [pytorch_model.bin](https://huggingface.co/microsoft/Florence-2-large/resolve/main/pytorch_model.bin)       | `/ComfyUI/models/LLM/`   |
| Florence2 Flux Large | [model.safetensors](https://huggingface.co/gokaygokay/Florence-2-Flux-Large/resolve/main/model.safetensors) | `/ComfyUI/models/LLM/`   |

#### 🎬 VIDEO
| Model         | Part              | Download Link                                                                                                                                                           | Installation Path                   |
| ------------- | ----------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------- |
| WAN2.1 i2v 480p | diffusion_models  | [Download](https://huggingface.co/Comfy-Org/Wan_2.1_ComfyUI_repackaged/resolve/main/split_files/diffusion_models/wan2.1_i2v_480p_14B_fp8_scaled.safetensors) | `/ComfyUI/models/diffusion_models/` |
|               | vae               | [Download](https://huggingface.co/Comfy-Org/Wan_2.1_ComfyUI_repackaged/resolve/main/split_files/vae/wan_2.1_vae.safetensors)                                           | `/ComfyUI/models/vae/`              |
|               | text_encoders     | [Download](https://huggingface.co/Comfy-Org/Wan_2.1_ComfyUI_repackaged/resolve/main/split_files/text_encoders/umt5_xxl_fp8_e4m3fn_scaled.safetensors)         | `/ComfyUI/models/text_encoders/`    |
|               | clip_vision       | [Download](https://huggingface.co/Comfy-Org/Wan_2.1_ComfyUI_repackaged/resolve/main/split_files/clip_vision/clip_vision_h.safetensors)                               | `/ComfyUI/models/clip_vision/`      |
| CogVideoX     | part 1            | [Download](https://huggingface.co/THUDM/CogVideoX1.5-5B-I2V/resolve/main/transformer/diffusion_pytorch_model-00001-of-00003.safetensors)                               | `/ComfyUI/models/CogVideo/`         |
|               | part 2            | [Download](https://huggingface.co/THUDM/CogVideoX1.5-5B-I2V/resolve/main/transformer/diffusion_pytorch_model-00002-of-00003.safetensors)                               | `/ComfyUI/models/CogVideo/`         |
|               | part 3            | [Download](https://huggingface.co/THUDM/CogVideoX1.5-5B-I2V/resolve/main/transformer/diffusion_pytorch_model-00003-of-00003.safetensors)                               | `/ComfyUI/models/CogVideo/`         |

#### 🧊 3D
| Model     | Download Link                                                                                             | Installation Path           |
| --------- | --------------------------------------------------------------------------------------------------------- | --------------------------- |
| Hunyuan3D | [hunyuan3d-dit-v2-0-fp16.safetensors](https://huggingface.co/Kijai/Hunyuan3D-2_safetensors/resolve/main/hunyuan3d-dit-v2-0-fp16.safetensors) | `/ComfyUI/models/diffusion_models/` |

#### 🖼️ UPSCALER
| Model                       | Download Link                                                                                             | Installation Path          |
| --------------------------- | --------------------------------------------------------------------------------------------------------- | -------------------------- |
| RealESRGAN_x2               | [RealESRGAN_x2.pth](https://huggingface.co/ai-forever/Real-ESRGAN/resolve/main/RealESRGAN_x2.pth)             | `/ComfyUI/models/upscale_models/` |
| #RealESRGAN_x4              | [RealESRGAN_x4.pth](https://huggingface.co/ai-forever/Real-ESRGAN/resolve/main/RealESRGAN_x4.pth)             | `/ComfyUI/models/upscale_models/` |
| #RealESRGAN_x8              | [RealESRGAN_x8.pth](https://huggingface.co/ai-forever/Real-ESRGAN/resolve/main/RealESRGAN_x8.pth)             | `/ComfyUI/models/upscale_models/` |
| #4x-UltraSharp              | [4x-UltraSharp.pth](https://huggingface.co/uwg/upscaler/resolve/main/ESRGAN/4x-UltraSharp.pth)                 | `/ComfyUI/models/upscale_models/` |
| #4x_RealisticRescaler_100000_G | [4x_RealisticRescaler_100000_G.pth](https://huggingface.co/uwg/upscaler/resolve/main/ESRGAN/4x_RealisticRescaler_100000_G.pth) | `/ComfyUI/models/upscale_models/` |
| #4x_NMKD-Siax_200k          | [4x_NMKD-Siax_200k.pth](https://huggingface.co/gemasai/4x_NMKD-Siax_200k/resolve/main/4x_NMKD-Siax_200k.pth)   | `/ComfyUI/models/upscale_models/` |
| #ESRGAN_4x                  | [ESRGAN_4x.pth](https://huggingface.co/Afizi/ESRGAN_4x.pth/resolve/main/ESRGAN_4x.pth)                         | `/ComfyUI/models/upscale_models/` |

---

### 🙏 Credits
*   m4d
*   comfyanonymous
*   kijai
*   Kosinkadink
*   WASasquatch
*   phytongosssss
*   cubiq
*   TheUpsider
*   BadCafeCode
*   AlekPet
*   Enrico
*   illyasviel
*   rgthree
*   ltdrdata
*   Fannovel16
*   City96
*   Crystian
*   ssitu
*   theUpsider
*   jags111
*   huchenlei
*   BlackForestLabs
*   Stability AI