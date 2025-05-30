
# Instrumentino GUI (Python 3.10 + wxPython 4.2.3)

Instrumentino is a modular open-source platform for graphical user interfaces designed to control experimental devices based on Arduino, which has been rewritten for the newer version of Python and wxPython libraries.

Original project link :https://github.com/yoelk/instrumentino.git

## Requirements

- Python 3.10
- [wxPython 4.2.3](https://wxpython.org/)

## Installation

git clone https://github.com/togiyako/instrumentino.git

cd instrumentino

# Development mode
pip install -e .

# Or conventional installation
pip install .

## Tests

To start testing, you need to follow these steps :
    - switch to developer mode;
    - install python3.10 and wxPython 4.2.3
    - run the command of your choice:
        - python test_system.py
        - cd documents/example_run_container.py/container.py
        - cd documents/example_run_ArduinoPins.py/ArduinoPins.py
