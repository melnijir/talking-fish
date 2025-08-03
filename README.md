# Talking fish for Home Assistant

This project is about converting a [Big Mouth Billy Bass](https://en.wikipedia.org/wiki/Big_Mouth_Billy_Bass) into a cool ChatGPT-powered assistant with integration into Home Assistant.

Due to the high price of the original model, an "Electronic Singing Plastic Fish" from Aliexpress is used instead. :blush:

The fish is controlled by a Raspberry Pi (in this example, a Raspberry Pi 3 is used).

## Installation
Clone the repository
```
git clone <rep_addr>
```
Prepare python environment and install necessary packages
```
python -m venv ./env
./env/bin/pip install --upgrade pip setuptools wheel
./env/bin/pip install paho-mqtt gTTS RPi.GPIO openai
sudo apt install mpg321 -y
```
