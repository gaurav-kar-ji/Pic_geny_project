# Pic Geny – Image Generation using Stable Diffusion XL

Pic Geny is a Google Colab–powered image generation pipeline built using **Stable Diffusion XL (SDXL)**.  
It generates high-quality, realistic images from text prompts using a two-stage diffusion process: **Base Model + Refiner Model**.

---

## Features

- ✔️ Stable Diffusion XL Base + Refiner execution
- ✔️ High-resolution text-to-image generation
- ✔️ GPU-accelerated inference (PyTorch + CUDA)
- ✔️ VRAM-optimized with attention slicing and FP16
- ✔️ Fully reproducible in Google Colab
- ✔️ Minimal dependencies and clean code

---

## Run in Google Colab

Click the link below to open and run the notebook instantly:

https://colab.research.google.com/drive/1nTK4FzvWsuzI4cHwwjtJFIVeVnHIKw61#scrollTo=OUnDUJJrpqB-

---

##  Tech Stack

| Component | Version |
|----------|---------|
| PyTorch | 2.4.0 (CUDA 12.1) |
| Diffusers | 0.29.2 |
| Transformers | 4.40.2 |
| Accelerate | 0.33.0 |
| xFormers | 0.0.27.post2 |
| PEFT | 0.11.1 |
| Safetensors | Included |

---

##  How It Works

The notebook follows these steps:

1. Install appropriate versions of required libraries
2. Load the **SDXL Base Model** and move it to the GPU
3. Load the **SDXL Refiner Model** and share components
4. Generate latent image from text prompt
5. Refine and enhance the final output
6. Save the generated image as `refined.png`

---

##  Example Prompt

Majestic lion standing in a jungle.
This prompt produces a realistic lion image with jungle background using SDXL refinement.

---

## Future Improvements

- Add UI controls for custom prompts
- Batch image generation support
- Save multiple image outputs
- Fine-tuning options using LoRA

---

## Support

If you like this project, please ⭐ the repository, it motivates future development!

