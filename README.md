# Sports Celebrity Image Classification

![License](https://img.shields.io/badge/License-MIT-blue.svg)

The Sports Celebrity Image Classification project is a machine learning-based application that classifies images of sports celebrities using deep learning techniques. It aims to accurately identify and classify sports celebrities based on input images.

## Features

- Image classification of sports celebrities
- Pre-trained models available
- Training option for custom models
- Evaluation and accuracy metrics

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository: https://github.com/sahilempire/Sports-Celebrity-Image-Classification


## Usage

1. Dataset preparation:

- Collect a dataset of sports celebrity images.
- Organize the dataset into train and test sets, with each celebrity in its respective class folder.

2. Pre-trained model usage:

- Run the following command to classify an image using a pre-trained model:

  ```
  python classify_image.py --image path/to/image --model pre-trained-model.h5
  ```

- Replace `path/to/image` with the path to your image and `pre-trained-model.h5` with the path to the pre-trained model.

3. Custom model training:

- Modify the `train_model.py` file to configure and train your custom model.
- Run the following command to train the custom model:

  ```
  python train_model.py --dataset path/to/dataset --model path/to/save/model
  ```

- Replace `path/to/dataset` with the path to your prepared dataset and `path/to/save/model` with the desired path to save the trained model.

For detailed usage instructions and options, refer to the [User Guide](docs/user-guide.md).

## Dataset

Please note that the dataset used in this project is not provided in this repository. You need to collect and prepare your own dataset of sports celebrity images for training and evaluation.

## Contributing

Contributions are welcome! If you have any ideas, improvements, or bug fixes, please submit a pull request. Make sure to follow the [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

