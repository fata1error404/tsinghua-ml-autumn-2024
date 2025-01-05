# Fine-Tuning Stable Diffusion for Style Transfer 

This repository contains supporting files for Machine Learning HW 3. The project was implemented using __Google Colab + Cloudfare + ComfyUI__.

Project structure:
- [`setup.ipynb`](setup.ipynb) – Jupiter notebook to setup ComfyUI
- [`fine-tune.json`](fine-tune.json) – ComfyUI pipeline to fine-tune the Flux model
- [`generate.json`](generate.json) – ComfyUI pipeline to generate fine-tuned images

<br />

### Manual
1. Run the setup file in Google Golab instance using Python 3 + T4 GPU runtime configuration.
2. Open ComfyUI using Cloudflare link.
3. Import pipelines.
4. Execute pipeline for fine-tuning.
5. Execute pipeline for image generation to test the fine-tuned model.