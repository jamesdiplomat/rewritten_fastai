# Notes on defaults / features

- fp16 training instead of fp32 (mixed precision)
- data augmentation has to be default
- running loss as training loss
- save / show validation loss and accuracy
- make it usable with different learning rate schedulers

# flaws to fix

- fix it so that we are not importing * as standard practice as in fastai!
- separate out fast model prototyping from flexible customization

# integrations list

- albumentations library
- pytorch lightning

