# MixingStyleTransfer


## ABSTRACT
We propose an end-to-end music mixing style transfer system that converts the mixing style of an input multitrack to that of a reference song. This is achieved with an encoder pre-trained with a contrastive objective to extract only audio effects related information from a reference music recording. All our models are trained in a self-supervised manner from an already-processed wet multitrack dataset with an effective data preprocessing method that alleviates the data scarcity of obtaining unprocessed dry data. We analyze the proposed encoder for the disentanglement capability of audio effects and also validate its performance for mixing style transfer through both objective and subjective evaluations. From the results, we show the proposed system not only converts the mixing style of multitrack audio close to a reference but is also robust with mixture-wise style transfer upon using a music source separation model.

Project page with samples : <https://jhtonyKoo.github.io/MixingStyleTransfer/>

Paper : 

Codes : <https://github.com/jhtonyKoo/music_mixing_style_transfer>

Supplementary Materials : <https://tinyurl.com/4math4pm>

