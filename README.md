# ResNet-18


<img width="1146" alt="image" src="https://user-images.githubusercontent.com/16959405/159809545-aa2712cc-b818-41dd-bff4-fbe04fd46b41.png">



Clone or download this repository
git clone [Github](https://github.com/rheyavlan/random)
Install dependencies
```
npm install
```

Command to start training : 
```
sbatch resnet_batch.sh
```

> Regularization

> Cutout









**Technologies and Tools used:**

Python
- torchvision
- pdb
- argparse
- numpy 
- tqdm
- torch
- torchvision 
- CSVLogger
- Cutout
- ResNet18

# from pyimagesearch import config
from torchvision.datasets import ImageFolder
from torch.utils.data import DataLoader
from torchvision import transforms
import matplotlib.pyplot as plt
import torch
