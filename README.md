# PyAirPods
> Reversing engineering AirPods with Python.

## Supported Devices

* AirPods 1st Generation

* AirPods 2nd Generation

* AirPods Pro

**I'm not going to do reversing enginnering AirPods Max.**

## Features

- Check battery status of Both units (also the battery case)

- Check which unit you are using

- Check charging status

### Todos

- Control the Noise Control of AirPods Pro

### How does it work?

[Real magic](https://github.com/adolfintel/OpenPods/blob/master/OpenPods/app/src/main/java/com/dosse/airpods/PodsService.java) comes from here.

## Build and run

### Tested environment

* [macOS Big Sur 11.1](https://www.apple.com/macos/big-sur/)

* [Python 3.8.6 for Darwin](https://www.python.org/downloads/release/python-386/)

* [MacBookPro15,1](https://support.apple.com/kb/SP776) and [Macmini9,1](https://www.apple.com/mac-mini/) (Tested on M1)

#### Windows

```powershell
git clone https://github.com/fxrcha/PyAirPods

cd PyAirPods

python3 -m pip install -r requirements.txt
```

#### macOS

```zsh
git clone https://github.com/fxrcha/PyAirPods

cd PyAirPods

python3 -m pip install -r requirements.txt
```

#### Linux

```bash
git clone https://github.com/fxrcha/PyAirPods

cd PyAirPods

python3 -m pip install -r requirements.txt
```

## Credits

[Apple](https://apple.com)

[OpenPods](https://github.com/adolfintel/OpenPods)
