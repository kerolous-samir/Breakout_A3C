# Breakout (A3C)

## Project Overview
This project implements **Asynchronous Advantage Actor-Critic (A3C)** for playing **Atari Breakout** using reinforcement learning.

## Features
- **Deep Learning Model**: Built using PyTorch.
- **A3C Algorithm**: Trains multiple agents asynchronously.
- **Custom Environment Enhancements**: Uses OpenAI Gym for training.
- **Custom Optimizer**: Implements shared Adam optimization.

## Installation
Clone the repository:
```bash
git clone https://github.com/kerolous-samir/Breakout_A3C.git
cd Breakout_A3C
```

Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage
### Training the Model
```bash
python main.py
```

### Testing the Model
```bash
python src/test.py
```

## Repository Structure
```
Breakout_A3C/
│── README.md
│── data/
│── src/
│   │── model.py
│   │── my_optim.py
│   │── train.py
│   │── test.py
│   │── envs.py
│── main.py
│── requirements.txt
│── LICENSE
│── .gitignore
```

## License
This project is licensed under the MIT License.

## Author
[Kerolous Samir](https://github.com/kerolous-samir)
