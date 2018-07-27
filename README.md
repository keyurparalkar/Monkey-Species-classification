## Dog breed identification

### Dataset information
The dataset consists of two files, training and validation. Each folder contains 10 subforders labeled as n0~n9, each corresponding a species form [Wikipedia's monkey cladogram](https://en.wikipedia.org/wiki/Monkey). Images are 400x300 px or larger and JPEG format (almost 1400 images). Images were downloaded with help of the googliser open source code.

> Label mapping: > > n0, alouatta_palliata 
> n1, erythrocebus_patas > n2, cacajao_calvus 
> n3, macaca_fuscata 
> n4, cebuella_pygmea 
> n5, cebus_capucinus 
> n6, mico_argentatus 
> n7, saimiri_sciureus 
> n8, aotus_nigriceps 
> n9, trachypithecus_johnii

For more information on the monkey species and number of images per class make sure to check monkey_labels.txt file.

### Aim
This dataset is intended as a test case for fine-grain classification tasks, perhaps best used in combination with transfer learning. 

### Libraries required
    pytorch
    numpy
    pandas
    matplotlib
    
### For installing pytorch
    conda install pytorch torchvision -c pytorch

### For running this project
1. Activate the fastai environment: `source activate pytorch`
2. Run the notebook: `jupyter notebook`