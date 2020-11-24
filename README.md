# EmotionNet
Human perception of emotion is based on facial expressions, and speech. Traditional emotion recognition techniques extract features from images or frames (in the case of a video). Our technique, based on the RAVDESS database, creates a hybrid model using features extracted from video, as well as audio provided in the dataset where emotions are being
acted out/sung by various actors. We’ve established baseline
accuracy with machine learning based approaches for only audio, only video, and audio-video combined features. Our hybrid fusion model, which outperforms all machine learning
based approaches, involves pre-trained ResNeXt-101 model-based image feature extraction, and MFCC based audio feature extraction, followed by hybrid fusion architecture for
feature combination and output. The dataset is available at -https://zenodo.org/record/1188976#.X62bLGgzaUk 

## Feature extraction pipeline
<img src="/plots/3.jpg">

## Fusion Model Architecture
<img src="/plots/2.jpg">

## Accuracy vs Epoch
<img src="/plots/1.jpg">
