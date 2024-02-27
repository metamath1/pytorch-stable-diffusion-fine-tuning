# pytorch-stable-diffusion-fine-tuning

- These two notebooks cover the process of fine-tuning StableDiffusion to a personal dataset.

- The Huggingface Diffusers documentation doesn't show how to fine-tune the model provided by Diffusers, only how to use a pre-written script file for fine-tuning.
    - https://huggingface.co/docs/diffusers/training/text2image
    - https://github.com/huggingface/diffusers/blob/main/examples/text_to_image/train_text_to_image.py

- There are some good tutorials based on keras, but it's hard to find a tutorial based on pytorch that shows how to code and fine-tune from scratch.
    - https://keras.io/examples/generative/finetune_stable_diffusion/

- The train_text_to_image[_lora].py provided by Diffusers has too much code that is not necessary for a learner who just wants to quickly grasp the logic, so it is necessary to organize it into a sequential notebook file.

- For that reason, this notebook breaks down train_text_to_image[_lora].py and describes how to quickly full-fine-tune a stable diffusion with minimal code required.

