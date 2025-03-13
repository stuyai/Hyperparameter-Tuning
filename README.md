# Hyperparameter Tuning with PyTorch and Optuna

This project demonstrates hyperparameter tuning for a CNN model on the MNIST dataset using PyTorch and Optuna.

## Overview
- **Model:** A simple CNN with two convolutional layers, batch normalization, and dropout.
- **Dataset:** MNIST (train, validation, and test splits).
- **Hyperparameters Tuned:** 
  - Learning Rate (lr)
  - Number of filters (num_filters)
  - Batch size (batch_size)
  - Dropout rate (dropout_rate)
  - Weight decay (weight_decay)

## Setup
- Install the required packages:
  ```
  pip install torch torchvision optuna
  ```
- Run the notebook `hyperparam_tuning.ipynb` to perform hyperparameter tuning and evaluate the model.

## Usage
1. Start by installing the dependencies.
2. Run the notebook cells sequentially to:
   - Load and preprocess data.
   - Define the CNN model.
   - Tune hyperparameters using Optuna.
   - Evaluate the final model on the test set.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss potential changes.

## Credits
Special thanks to Otzar Jaffe for making the lesson.

