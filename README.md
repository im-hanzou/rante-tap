# WInnode Project TAP-TAP ONCHAIN BOT

This is a Python script for automating TAP=TAP clicks on the WInnode Project platform.

## Features

- Automatically perform TAP=TAP clicks on the WInnode Project platform.
- Supports multiple accounts with JWT token authentication.
- Customizable click intervals and energy thresholds.
- Colorful console output for better visualization.

## Installation

1. Clone this repository to your local machine.
2. Install the required dependencies using pip:

pip install -r requirements.txt


## Usage
![Cara Mengambil Token](https://github.com/Winnode/rante-tap/raw/main/cara%20ambil%20token.png)
1. Prepare your JWT tokens and store them in a file named `token.json`.
2. Customize the configuration parameters in the `config.json` file according to your preferences.
3. Run the script:

python main.py

4. Sit back and let the bot perform TAP=TAP clicks automatically!


## Configuration

You can customize the behavior of the bot by modifying the parameters in the `config.json` file:

- `interval`: Interval between each click attempt (in seconds).
- `sleep`: Duration to wait when energy is insufficient (in seconds).
- `min_energy`: Minimum energy threshold for initiating energy boost.
- `click_range`: Range of clicks to perform per attempt (start and end values).

## Credits

- Author: [@WinNode](https://twitter.com/WinNode)
- Support: 0xde260429ef7680c7a43e855b5fcf619948f34e2a



