# Description

This repo contains a list of artists whose names can be added to Stable Diffusion prompts to change the art style. Comparison images are provided to give a rough idea of how the style changes.

All images are generated with model 1.4 and the following parameters:

Seed: 0
Size: 512x512
CSG: 7.5
Sampling Steps: 30

#### Note on Bias and Representation

Most of these artists are primarily character artists, and most of the characters they draw are women. Unfortunately, because Stable Diffusion's training set is largely biased with images of white people, the prompt "beautiful woman" basically only gives you white women. In addition, because many of these artists only make art of light-skinned people, even if your prompt would otherwise produce a dark-skinned person, the addition of the artist name turns them white or asian. It is what it is.

The baseline example images are meant to be unstylized versions of the subjects an artist already captures. The lack of diversity in these images reflects that. Hopefully the model can become more all-inclusive in the future.

Additionally, if you'd like more diverse artists on this list, feel free to open a pull request.

# Contributing

If there is an artist that the model knows about that you think should be on this list, you can open a pull request to add them.

All types of artists are welcome. A prompt matrix image like the ones below should be provided. The prompt should reflect the artist's primary subjects. Make sure you use the generation parameters listed above.

# Artists

### Akihiko Yoshida
@(|Akihiko Yoshida) (male|female) fantasy character
![](images/akihiko_yoshida.jpg)

### Alphonse Mucha
@woman, hair, flowers, (|Alphonse Mucha)
![](images/alphonse_mucha.jpg)

### Artgerm
@(|Artgerm) (male|female) superhero
![](images/artgerm.jpg)

### Conrad Roset
@beautiful woman, (|Conrad Roset)
![](images/conrad_roset.jpg)

### Greg Rutkowski
@(|Greg Rutkowski), (sail ship|landscape|witch)
![](images/greg_rutkowski.jpg)

### Ilya Kuvshinov
@beautiful woman, face, hair, (|Ilya Kuvshinov)
![](images/ilya_kuvshinov.jpg)

### Krenz Cushart
@girl in fantasy city, (|Krenz Cushart)
![](images/krenz_cushart.jpg)

### Michael Garmash
@beautiful woman in nature, pose, (|Michael Garmash)
![](images/michael_garmash.jpg)

