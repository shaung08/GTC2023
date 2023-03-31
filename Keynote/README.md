# Keynote3D by AI: Using Generative AI and NeRFs for Building Virtual Worlds, with Q&A in Ja

## software platform (end-to-end)

### Holoscan
Description: real time sensor process system.
hardware: holoscan igx orin
software: holoscan igx orin developer kits

### Nvidia Parabrivks
description: end to end gene analysis platform

### Nvidia DGX cloud 
Description: Use to run Nvidia AI enterprise. Already build on Google GCP cloud, Azure cloud, Oracle cloud.

### Nvidia AI foundation
Include: Nemo, Picasso, bionemo
#### Nemo
Support to train custom language model like (chat-gpt), also can set the boundry to avoid except reaponse(bussniess secret).
#### Picasso
Support to genertae image(diffusion v2.0), video(), and 3D resource
use case: 
1. gettyimages: Use picasso to build Editfy-Image and Edify-Video genrative model.
2. shutterstock: Develop Editfy-3D generative model. Help building 3D model creation, and using on omniverse and digital twins.
3. Adobe: Generate video and images

#### bionemo
Assist drug develop.

### Nvidia issac sim
Use omniverse to generate data to train dactory robots

### grammarly
### tabnine
Description: help developer write code
### omneky:
Description: generte custonmize ads and copy
### core.ai 
### jasper
### Insilico
Description: Use AI to accelerate drug design
### Absci
Description: Use AI to predict therapeutic antibodies

## software toolkit
### Nvidia software tool:
1. spark-rapids: big data data preprocessing  lib
2. raft:
3. riva:
4. cuOpt:
5. CV-cuda: image preocess libary. Run image process in GPU.(3.6x faster)
6. VPF: video preocess libary
7. cuLitho: accerlate computed lithography (TSMC)

## hardware
### DGX:
GPU: 8張H100(H100有 transform module for chatgpt)，H100之間用NVLINK連接 (H100有 transform module for chatgpt)
### Grace CPU
### blue field
### Nvidia L4 - 120X
Description: for video decoding transcoding, video content moderation
Spec: 8-GPU 
### Nvidia L40
Description: graph rendering, generative AI text-to-video. Inference service. Ten times the performance of Nvidia's T4.
### Nvidia H100 NVL -10x
Description: The current support GPT3 server is HGX A00. Nvidia H100 NVL 10x faster than HGX A00
### Grace Hopper
將cpu 和 gpu 之間溝通優化，比起傳統pcie介面快7倍

##　補充
### annouce release model:
1. GPT3-LLM

### tech:
1. ETA prediction
