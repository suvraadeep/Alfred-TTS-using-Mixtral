# Alfred using Mixtral 8x7B with Low Latency TTS

# How To Run 
1. Clone This repo
2. Before running:
- create a virtual env
- paste this over your terminal `conda install pytorch==1.13.1 torchvision==0.14.1 torchaudio==0.13.1 pytorch-cuda=11.7 -c pytorch -c nvidia`
- `pip install -r requirements.txt`
3. create a new folder "checkpoints" (I couldn't upload this here as the file size is> 400B
4. Download checkpoints from HERE: https://myshell-public-repo-hosting.s3.amazonaws.com/checkpoints_1226.zip
5. Unzip to Checkpoints (basespeakers + converter)
6. Install LM Studio and download Bloke Dolphin Mistral 7B V2 (https://huggingface.co/TheBloke/dolphin-2.2.1-mistral-7B-AWQ) and create a server
7. RUN `talk.py` or `voice69.py`
