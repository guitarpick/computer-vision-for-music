# Computer Vision for Music Identification



by Yan Ke, [Derek Hoiem](http://dhoiem.cs.illinois.edu/), and [Rahul Sukthankar](http://www.cs.cmu.edu/~rahuls/)

Abstract:

We describe how certain tasks in the audio domain can be effectively addressed using computer vision approaches. This paper focuses on the problem of music identification, where the goal is to reliably identify a song given a few seconds of noisy audio. Our approach treats the spectrogram of each music clip as a 2-D image and transforms music identification into a corrupted sub-image retrieval problem. By employing pairwise boosting on a large set of Viola-Jones features, our system learns compact, discriminative, local descriptors that are amenable to efficient indexing. During the query phase, we retrieve the set of song snippets that locally match the noisy sample and employ geometric verification in conjunction with an EM-based "occlusion" model to identify the song that is most consistent with the observed signal. We have implemented our algorithm in a practical system that can quickly and accurately recognize music from short audio samples in the presence of distortions such as poor recording quality and significant ambient noise. Our experiments demonstrate that this approach significantly outperforms the current state-of-the-art in content-based music identification.


Y. Ke, D. Hoiem, and R. Sukthankar. In Proceedings of Computer Vision and Pattern Recognition, 2005. [PDF 240KB]



[Source](http://www.cs.cmu.edu/~yke/musicretrieval/)