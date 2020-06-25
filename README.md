# MIR-music-information-retrieval-course

This repository has the theory and practice of my course of MIR.

# Table of Contents

1. [Intro](#Intro)
2. [DSP](#DSP)
3. [Selectors](#Selectors)
4. [Pseudo-selectors](#Pseudo-selectors)
5. [Size and colors](#Size-and-colors)
6. [Box Model](#Box-Model)
7. [Box](#Box)
8. [Text](#Text)
9. [Positioning](#Positioning)
10. [Dimensions](#Dimensions)
11. [BACKGROUNDS](#BACKGROUNDS)
12. [UI](#UI)

## Intro?

The way we listen and understand music is based on how it unfolds over time and frecuency.
Time frecuencies representations in spectral analisys form the basics of many algorithms for extracting information.

## DSP

Digital signal procesing.
Sound consists of repeating patters of higth and low pressure in air.
When we play a string of a guitar, it sets into motion air molecules. This motion propagates through the air. Repeating patters of higth and low molecular density (high and low preasure).
When that reaches our ears, it is converted to mechanical energy in our eardrum and them to electrical signals that are interpreted by our brain by an organ called cochlea.

That sound preasure waves can be captured by a microphone in an analogous way. The sound preasures changes moves the diaphragm of the microphone, and it converted to an electrical signal.

when processing sound digitally, this electrical signal is converted to a discreet sequence of numbers by a device called an analog to digital converter.

A sound is represented digitally by a large array of numbers, we call SAMPLES. In the CD for examples, that store a digital representation of audio we have a sample rate of 44100 samples per second and each sample is represented by a 16-bit integer that we frecuently convert these integer in floating point numbers between -1 and 1 becouse is easier to handle for DSP (we call this QUANTIZATION).

![alt text](/img/sampling-a-sine-wave.png "Sampling a sine wave")

So we have two term in the digitalization of audio: SAMPLING and QUANTIZATION (sample rate and bits).

(poner diferentes audios con diferentes calidades)

## Pitch and Time

(poner el feliz cumpleanos tocado con un saxo o piano y un sin)

We recognize the melody even if the sound was composing for various instruments (poner la cancion de los simpsoms con la partitura de youtube)
you recognize even its played by the simplest representation of sound.

The animals produce periodic sounds to make them identificable from other sourses so animal hearing systems have evolved to be good at detecting periodic sound.

When the soun is repeating more than 10 to 20 times in a second our perseptual system does not hear the individual repeatred segments but instead, fuses the repetition and we hear a single sound that s caracterized by a cuantity we call pitch. Pitch is the fundamental frecuency of repetitition

## Spectrogram

Is a fundamental concept in DSP
