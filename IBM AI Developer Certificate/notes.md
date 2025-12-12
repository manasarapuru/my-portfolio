### Core Generative AI Models
1. Variation Autoencoders (Most Popular)
   - work with images, text, audio
   - rapidly reduce dimensionality
   - Steps:
     - 1: Encoder (self-sufficient neural network) studies probabilitist distribution of the input data to identify the useful data values)
     - 2: Decoder (also self-sufficient neural network) decompresses the compressed representation in the latent space to generate the desired output
     - Algorithms use max likelihood principle
     - Used in: image analysis, data compression and anomally detection 
2. Generative Adversarial Networks
     - works with images, text
     - 2 CNNs
     -   CNN #1 generates data
     -   CNN #2 plays devil's advocate and tries to distinguish between real and fake data
     -   GANs can generate new realistic-looking images, perform a style transfer or image to image translation and even create deep fakes
3. Transformer Based Models
     - Transformers were built with attention mechanisms that could focus on the most valuable parts of the text while filtering out the unnecessary elements
     - This allowed transformers to model long-term dependencies in text
     - Two-stack transformer architecture uses an encoder-decoder mechanism to generate coherent and contextually relevant text.
4. Diffusion Models
     - these models try to prevent information loss
     - work with images
     - Steps:
       - 1. forward diffusion, in which algorithms gradually add random noise to training data.
       - 2. everse diffusion, in which algorithms turn the noise around to recover the data and generate the desired output
