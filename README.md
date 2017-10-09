This is the defense solution of team TSAIL in the NIPS 2017: Defense Against Adversarial Attack competition. 

Our basic idea is to put a denoiser before the a baseline neural network. The denoiser is trained to reduce the pertubation of adversarial examples. And a denoiser is specifically trained for a baseline neural network.

The solution is an ensemble of 4 independent models and their denoiser (ResNet, ResNext, InceptionV3, inceptionResNetV2). 

The weights can be downloaded from [here](https://pan.baidu.com/s/1hs7ti5Y) or [here](https://www.dropbox.com/sh/q9ssnbhpx8l515t/AACvjiMmGRCteaApmj1zTrLTa?dl=0)

The team members are:

Fangzhou Liao

Ming Liang

Tianyu Pang

Yinpeng Dong



The framework is inherited from https://github.com/rwightman/pytorch-nips2017-defense-example.

