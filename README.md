# LivePortrait: Efficient Portrait Animation with Stitching and Retargeting Control

---

**Important Note:** This repository is a fork of the original [LivePortrait](https://huggingface.co/spaces/KwaiVGI/LivePortrait) project by KwaiVGI. It is not intended to be mistaken for a separate, original work. All credit for the core technology and initial implementation goes to the original authors.

---

## Introduction 📖
This repository, named **LivePortrait**, contains the official PyTorch implementation of our paper [LivePortrait: Efficient Portrait Animation with Stitching and Retargeting Control](https://arxiv.org/pdf/2407.03168). We are actively updating and improving this repository. If you find any bugs or have suggestions, welcome to raise issues or submit pull requests (PR) 💖.

---

## Live Portrait

### Metadata
- **emoji:** 🤪
- **colorFrom:** red
- **colorTo:** yellow
- **sdk:** gradio
- **sdk_version:** 4.37.2
- **app_file:** app.py
- **pinned:** false
- **disable_embedding:** true
- **tags:**
  - Multimodal
  - Motion control
  - Image-to-Video
  - Video-to-Video
  - language models
  - LLMs
- **short_description:** Apply the motion of a video on a portrait

---

## Should run this on GPU
## Installation and Usage

### Prerequisites
Ensure you have `ffmpeg` and `ffprobe` installed:
```bash
sudo apt-get update
sudo apt-get install ffmpeg ffprobe git-lfs
```

### Clone and Setup
Clone the repository and install the required dependencies:
```bash
git clone https://huggingface.co/spaces/svjack/LivePortrait && cd LivePortrait
pip install -r requirements.txt
```

### Run with Gradio Web UI
To launch the Gradio web interface:
```bash
python app.py --share
```

### Run in CLI
For command-line interface usage:
```bash
python inference.py -s assets/examples/source/s0.jpg  -d assets/examples/driving/d0.mp4 -o case0
```
