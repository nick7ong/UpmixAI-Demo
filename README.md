# UpmixAI-Demo
### Quick Links
- Try it out for yourself here --> [upmixai.glitch.me](https://upmixai.glitch.me/)
- Check out some examples of upmixed audio in the examples folder here -->
  
### Stereo-to-Surround Sound Upmixing Using a Hybrid AI and Ambience Extraction Algorithm
A critical step in upmixing stereo content to a higher channel format lies in decomposing the stereo signal into distinct musical stems. Existing stereo-to-surround sound upmixing algorithms employ methods such as passive surround decoding (PSD) and primary-ambience extraction (PAE). These methods are constrained by audio quality as well as phase and amplitude correlation between the stereo channels, leading to sub-optimal stem extraction. This paper introduces UpmixAI, a hybrid system utilizing artificial intelligence (AI) for primary source separation alongside a frequency-domain auto- and cross-correlation algorithm for ambience extraction. In its design, our system aims to address the limitations found in existing systems by potentially enhancing the accuracy and performance of the primary and ambient stem extraction. Our upmixing solution is delivered through a web-based application, designed for a simple and intuitive user experience. User requests, controller logic and audio processing are handled on an external server to ensure efficient and high-quality conversion from stereo to 5.1 surround sound and beyond. Ultimately, our system aims to democratize spatial audio by making it accessible to a wider audience without the need for extensive technical knowledge or sophisticated software.
  
### System Diagram
Below outlines the relationship and interactions between the different components of the system.
![upmixai-system](https://github.com/nick7ong/UpmixAI/assets/105762930/b8ff3b72-fd7b-41f2-95cc-99a5ad9244b9)

## The Mixing Algorithms
This project hosts a variety of upmixing and downmixing algorithms for stereo/surround audio.
### Stereo to 5.1 Surround
![2to51-algorithm](https://github.com/nick7ong/UpmixAI/assets/105762930/bfa6841c-1793-4738-982d-86419dfe1709)

### Stereo to Binaural Stereo
![2tob-algorithm](https://github.com/nick7ong/UpmixAI/assets/105762930/d26bc4ce-a881-4710-85ff-be85a3423adf)

### 5.1 Surround to Binaural Stereo
![51tob2-algorithm](https://github.com/nick7ong/UpmixAI/assets/105762930/4e96be34-ed62-467f-8ed3-cb37cc59a41b)

### 5.1 Surround to Stereo
![51to2-algorithm](https://github.com/nick7ong/UpmixAI/assets/105762930/ad991d58-f918-4364-9bd5-6227d06a04d0)
