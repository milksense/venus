# Venus

Venus is a neural network aim assist that uses real-time object detection accelerated with CUDA on Nvidia GPUs. (Fortnite only, WQHD+)

![thumbnail](https://i.imgur.com/bhpOHB8.png)

### Requirements

[Python](https://www.python.org/downloads/) 3.8 or later.

### Installation

```
pip install -r requirements.txt
```

### Usage

```
python venus.py
```

To update sensitivity settings:

```
python venus.py setup
```

To collect image data for annotating and training:

```
python venus.py collect_data
```

### Contributing

Pull requests are welcome. If you have any suggestions, questions, or find any issues, please open an [issue](https://github.com/milksense/venus/issues) and provide some detail.
If you find this project interesting or helpful, please star the repository.

### Misc

This repo is a improvement fork of [lunar](https://github.com/zeyad-mansour/lunar).
