# Tello Drone Barcode Scanning
The sample code is ported from https://github.com/dji-sdk/Tello-Python/tree/master/Tello_Video. 

## Requirements
- Python 3.7
- [h264decoder](https://github.com/DaWelter/h264decoder)

## Installation

```
pip install -r requirements.txt
```

## Usage

Get a valid license from https://www.dynamsoft.com/customer/license/trialLicense and then update the code:

```py
self.reader.init_license('LICENSE-KEY') 
```

Run the GUI app:

```
python main.py
```

![Tello drone barcode scanning](https://www.dynamsoft.com/codepool/wp-content/uploads/2020/11/tello-drone-barcode.png)

## Blog
[How to Make Tello Drone Capable of Barcode Scanning through Python](https://www.dynamsoft.com/codepool/dji-tello-drone-barcode-scanning-py.html)
