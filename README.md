whisper small 모델을 밀크티초등 쏙쏙words 단어들을 미국인 tts와 한국어 tts로 발음한 wav 파일 1,937 * 2 개의 파일로 파인 튜닝함.
```
epochs = 3
batch_size = 8
train_sample_size = 4000
optimizer = AdamW
learning_rate = 1e-5
resampling = 16000hz
```
```Best Training Loss: 0.0323933675793319```
허깅페이스 : oxorudo/whisper_ssokssokword
모델 safetensors는 허깅페이스에 있음.
