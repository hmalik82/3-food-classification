# CNN on Custom Image Dataset (PyTorch)

This notebook trains a Convolutional Neural Network (CNN) using PyTorch on a custom image dataset organized into folders by class.

## Dataset Structure
```
data/
├── class1/
│ ├── image1.jpg
│ └── ...
├── class2/
│ └── ...
...
```


## Features
- Custom dataset loading using PyTorch's `Dataset` and `DataLoader`
- Data transformations using `torchvision.transforms`
- CNN model defined with `torch.nn`
- Model summary via `torchinfo`
- Training with performance tracking via `tqdm`
- Evaluation and visualizations using `matplotlib`

## Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```

or manually:
```bash
pip install torch torchvision torchinfo matplotlib numpy tqdm requests Pillow
```

