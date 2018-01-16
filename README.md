# Bluefruit-FPGA
VHDL module for interfacing Adafruit's Bluefruit LE UART friend with an FPGA

Current Features:
1) Output for each button of the controller app
2) 8-bit RGB outputs for the color selector app
3) User selectable clock frequency (tested at 50MHz, 66.667MHz, 100MHz, 200MHz, and 300MHz)

Future Improvements:
1) Utilize checker byte in each command for robustness
2) Incorporate gyro and accelerometer data from app device