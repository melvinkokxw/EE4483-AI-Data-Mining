# Cats vs Dogs classifier

EE4483 Artificial Intelligence & Data Mining Project Option 2

# Usage

This code was tested on Python 3.9.6, but should work for most Python version >= 3.7

1. Install required Python packages:
```bash
python -m pip install -r requirements.txt
```

2. Install Pytorch and Torchvision based on your system. Instructions can be found on the Pytorch website [here](https://pytorch.org/get-started/locally/). This code was tested with Pytorch == 1.1.0 with CUDA >= 11.3

3. Extract dataset into same folder as notebook. Folder should look something like this:

```
./
├─ datasets/
│  ├─ test/
│  ├─ train/
│  │  ├─ cats/
│  │  ├─ dogs/
│  ├─ val/
│  │  ├─ cats/
│  │  ├─ dogs/
├─ main.ipynb
├─ README.md
```

4. Run `main.ipynb`. The sections `Setup environment` and 1 - 3 must be run before any other code.
   * To train and test model for Cats vs Dogs classifier, run sections 4 - 5.
   * To train and test model for CIFAR-10, run sections 6 - 7