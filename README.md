# AudioSignalProcessingForML

Code and slides of my YouTube series called "[Audio Signal Proessing for Machine Learning](https://www.youtube.com/playlist?list=PL-wATfeyAMNqIee7cH3q1bh4QJFAaeNv0)"

This repository is a comprehensive collection of resources, code, and explanations for understanding and implementing audio signal processing techniques, with a focus on applications in machine learning. It serves as a learning guide, starting from the fundamentals of sound and waveforms and progressing to advanced feature extraction methods.

## Course Structure

### Foundational Concepts

1.  **Overview:** _[Video][1yt] | [Slides][1sl]_
2.  **Sound and waveforms:** _[Video][2yt] | [Slides][2sl]_
3.  **Intensity, loudness, and timbre:** _[Video][3yt] | [Slides][3sl] | [Notebook][3nb]_
4.  **Understanding audio signals:** _[Video][4yt] | [Slides][4sl]_

---

### Feature Extraction Theory

5.  **Types of audio features for ML:** _[Video][5yt] | [Slides][5sl]_
6.  **How to extract audio features:** _[Video][6yt] | [Slides][6sl]_
7.  **Time-domain audio features:** _[Video][7yt] | [Slides][7sl]_

---

### Time-Domain Implementation

8.  **Implementing the amplitude envelope:** _[Video][8yt] | [Notebook][8nb]_
9.  **RMS energy and zero-crossing rate:** _[Video][9yt] | [Notebook][9nb]_

---

### Frequency-Domain Concepts

10. **Fourier Transform: The Intuition:** _[Video][10yt] | [Slides][10sl]_
11. **Complex numbers for audio signal processing:** _[Video][11yt] | [Slides][11sl]_
12. **Defining the Fourier transform using complex numbers:** _[Video][12yt] | [Slides][12sl] | [Notebook][12nb]_
13. **Discrete Fourier Transform:** _[Video][13yt] | [Slides][13sl]_

---

### Frequency-Domain Implementation

14. **Extracting the Discrete Fourier Transform:** _[Video][14yt] | [Notebook][14nb]_
15. **Short-Time Fourier Transform explained easily:** _[Video][15yt] | [Slides][15sl]_
16. **Extracting Spectrograms from Audio with Python:** _[Video][16yt] | [Notebook][16nb]_
17. **Mel Spectrogram Explained Easily:** _[Video][17yt] | [Slides][17sl]_
18. **Extracting Mel Spectrograms with Python:** _[Video][18yt] | [Notebook][18nb]_
19. **MFCCs Explained Easily:** _[Video][19yt] | [Slides][19sl]_
20. **Extracting MFCCs with Python:** _[Video][20yt] | [Notebook][20nb]_
21. **Frequency-Domain Audio Features:** _[Video][21yt] | [Slides][21sl]_
22. **Implementing Band Energy Ratio from Scratch with Python:** _[Video][22yt] | [Notebook][22nb]_
23. **Spectral centroid and bandwidth:** _[Video][23yt] | [Notebook][23nb]_

---

### Audio examples

* [**`audio_resources/`**](<audio_resources/>): A collection of .wav files used for the examples in the notebooks.

<!-- Reference links for every chapter:
YouTube videos (#yt), PDF-file slides (#sl) and Jupyter Notebooks (#nb) -->
[1yt]: https://www.youtube.com/watch?v=iCwMQJnKk2c
[1sl]: <1- Overview/Audio Signal Processing for Machine Learning.pdf>

[2yt]: https://www.youtube.com/watch?v=bnHHVo3j124
[2sl]: <2- Sound and waveforms/2- Sound and waveforms.pdf>

[3yt]: https://www.youtube.com/watch?v=Jkoysm1fHUw
[3sl]: <3- Intensity, loudness, and timbre/Intensity, loudness, and timbre.pdf>
[3nb]: <3- Intensity, loudness, and timbre/intensity_and_timbre.ipynb>

[4yt]: https://www.youtube.com/watch?v=daB9naGBVv4
[4sl]: <4- Understanding audio signals/Understanding audio signals.pdf>

[5yt]: https://www.youtube.com/watch?v=ZZ9u1vUtcIA
[5sl]: <5- Types of audio features for ML/Types of Audio Features for ML.pdf>

[6yt]: https://www.youtube.com/watch?v=8A-W1xk7qs8
[6sl]: <6- How to extract audio features/How to extract audio features.pdf>

[7yt]: https://www.youtube.com/watch?v=SRrQ_v-OOSg
[7sl]: <7- Time-domain audio features/Time-domain audio features.pdf>

[8yt]: https://www.youtube.com/watch?v=rlypsap6Wow
[8nb]: <8- Implementing the amplitude envelope/Implementing the amplitude envelope.ipynb>

[9yt]: https://www.youtube.com/watch?v=EycaSbIRx-0
[9nb]: <9- RMS energy and zero-crossing rate/RMS Energy and Zero-Crossing Rate.ipynb>

[10yt]: https://www.youtube.com/watch?v=XQ45IgG6rJ4
[10sl]: <10 - Fourier Transform: The Intuition/Demystifying the Fourier Transform The Intuition.pdf>

[11yt]: https://www.youtube.com/watch?v=DgF4m0AWCgA
[11sl]: <11 - Complex numbers for audio signal processing/Complex numbers.pdf>

[12yt]: https://www.youtube.com/watch?v=KxRmbtJWUzI
[12sl]: <12- Defining the Fourier transform using complex numbers/Defining the Fourier Transform Using Complex Numbers.pdf>
[12nb]: <12- Defining the Fourier transform using complex numbers/Defining the Fourier Transform Using  Complex Numbers.ipynb>

[13yt]: https://www.youtube.com/watch?v=ZUi_jdOyxIQ
[13sl]: <13- Discrete Fourier Transform/Discrete Fourier Transform.pdf>

[14yt]: https://www.youtube.com/watch?v=R-5uxKTRjzM
[14nb]: <14- Extracting the Discrete Fourier Transform/Visualising the Power Spectrum.ipynb>

[15yt]: https://www.youtube.com/watch?v=-Yxj3yfvY-4
[15sl]: <15 - Short-Time Fourier Transform explained easily/Short-Time Fourier Transform Explained Easily.pdf>

[16yt]: https://www.youtube.com/watch?v=3gzI4Z2OFgY
[16nb]: <16 - Extracting Spectrograms from Audio with Python/Extracting Spectrograms from Audio with Python.ipynb>

[17yt]: https://www.youtube.com/watch?v=9GHCiiDLHQ4
[17sl]: <17 - Mel Spectrogram Explained Easily/Mel Spectrograms Explained Easily.pdf>

[18yt]: https://www.youtube.com/watch?v=TdnVE5m3o_0
[18nb]: <18 - Extracting Mel Spectrograms with Python/Extracting Mel Spectrograms.ipynb>

[19yt]: https://www.youtube.com/watch?v=4_SH2nfbQZ8
[19sl]: <19- MFCCs Explained Easily/Mel-Frequency Cepstral Coefficients Explained Easily.pdf>

[20yt]: https://www.youtube.com/watch?v=WJI-17MNpdE
[20nb]: <20- Extracting MFCCs with Python/Extracting MFCCs.ipynb>

[21yt]: https://www.youtube.com/watch?v=3-bjAoAxQ9o
[21sl]: <21 - Frequency-Domain Audio Features/Frequency-domain audio features.pdf>

[22yt]: https://www.youtube.com/watch?v=8UJ8ZDR7yUs
[22nb]: <22 - Implementing Band Energy Ratio from Scratch with Python/Implementing band energy ratio from scratch.ipynb>

[23yt]: https://www.youtube.com/watch?v=j6NTatoi928
[23nb]: <23- Spectral centroid and bandwidth/Spectral centroid and bandwidth.ipynb>