# IoT_energystorage_charger_ble

- [NRF52832 DK pinout](https://os.mbed.com/platforms/Nordic-nRF52-DK/)
- [NRF52832 DK schematics](https://devzone.nordicsemi.com/cfs-file/__key/communityserver-discussions-components-files/4/PCA10040_5F00_Schematic_5F00_And_5F00_PCB.pdf)

# HW design

- [BLE 2.4GHz antenna design](https://www.infineon.com/dgdl/Infineon-AN91445_Antenna_Design_and_RF_Layout_Guidelines-ApplicationNotes-v09_00-EN.pdf)

# SW progress

## Power Receiving Unit PCB

Progress SW features implemented in the PRU firmware.

- [x] Deep sleep mode
- [x] ADC (read voltages)
- [x] UART (debugging)
- [x] ADV BLE messages
- [x] GPIO
- [x] State diagram
- [ ] I2C
