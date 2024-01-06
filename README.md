# gnome-randr.py

`gnome-randr.py` is a Python script for managing screen orientation and arrangement in GNOME, particularly on Wayland. It offers a command-line interface to adjust display settings, providing functionality that is especially useful in environments where traditional tools like `xrandr` are not directly applicable.

## Features

- Adjust screen orientation (normal, left, right, inverted).
- Manage multiple display configurations.
- Position screens relative to each other (e.g., above, below, left, right).
- Apply scaling to adjust display resolutions effectively.
- Store and recall current configurations for easy switching.
- Designed specifically for GNOME on Wayland.

## Requirements

- Python: Ensure Python is installed on your system.
- GNOME on Wayland: This script is intended for use with GNOME running on the Wayland display server.

## Installation

1. Download `gnome-randr.py` from the repository.
2. Place the script in a suitable directory, such as `/usr/local/bin` for system-wide accessibility.
3. Make the script executable:
`chmod +x /path/to/gnome-randr.py`

## Usage
`/path/to/gnome-randr.py --help` for specific options

## Contributing

Contributions to improve `gnome-randr.py` are welcome. Please feel free to fork the repository, make your changes, and create a pull request with your improvements.

## License

The project is open-source and available under the MIT License. See the LICENSE file for more details.

## Acknowledgements

- Thanks to all contributors who have helped in developing and refining `gnome-randr.py`.
- This tool is built to assist users of GNOME on Wayland and aims to simplify display management on this platform.
