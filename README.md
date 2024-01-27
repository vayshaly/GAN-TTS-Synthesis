# GAN-TTS-Synthesis
Synthesize realistic voices from a GAN-TTS


## Project Overview

This repository contains code for synthesizing realistic voices from a GAN-TTS (Generative Adversarial Network for Text-to-Speech) model.

### Task Description

Synthesize realistic voices from a GAN-TTS. The architecture includes a feed-forward generator producing raw speech audio and an ensemble of discriminators.
The discriminators analyze the audio in terms of general realism and how well it corresponds to the given utterance.

### gan_tts.ipynb 
contains 
Implementation of the generator model.
Implementation of the discriminator model.
Custom dataset class for LJ Speech with padding.

### Evaluation Metrics
Mean Opinion Score (MOS) is used as an evaluation metric for the generated speech.
