# recurrent_vision_transformer
Let's train vision transformers for cifar 10! 

This is an unofficial and elementary implementation of `An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale`.

I use pytorch for implementation.

# Usage
`python train_cifar10.py --net vit` # Normal Vision Transformer

`python train_cifar10.py --net recurrentvit` # Standard Recurrent Unrolling

`python train_cifar10.py --net recurrentbiovit` # Biological Unrolling 

# Results..

|             | Accuracy |
|:-----------:|:--------:|
| ViT patch=2 |    80%    |
| ViT patch=4 |    80%   |
| ViT patch=8 |    30%   |
|   resnet18  |  93% ;)  |
