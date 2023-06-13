# AI-Chan
AI-Chan is an innovative AI-powered chatbot program designed to integrate voice- and image-generation. 
<p align="center"><img src="assets/cover.png" width="500" ></p>

# Announcement
You may not run it successfully, I plan to rewrite the code later.
AI-Chan is still a PROTOTYPE (I only spent 6 hours on this...), SST is not done yet.

# Prerequisite
* Python 3.10
* [Stable-Diffusion webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) installed in `stable-diffusion-webui` folder. And make sure you select [`anything-v5`](https://huggingface.co/stablediffusionapi/anything-v5) model.
* Your OpenAI API key in each file in `src/gpt` folder

# How to run
1. Open Stable-Diffusion webui first (add `--api` at the end)
> `$ ./webui.sh --api`
2. Run `gui_main.py` in `src` folder 
> `$ python gui_main.py`
