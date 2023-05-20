# ST25R3911B-STM32Cube

The code implements the RF/NFC abstraction layer (RFAL) APIs for the ST25R3911B component.

Forked from https://github.com/stm32duino/ST25R3911B

This code uses STM32Cube HAL API instead of Arduino API.

# Dependencies

The ST25R3911B library requires the following STM32duino library:

* STM32duino NFC-RFAL: https://github.com/stm32duino/NFC-RFAL

# Usage

## Constructor
```cpp
RfalRfST25R3911BClass(SPI_HandleTypeDef* hspi, GPIO_TypeDef* cs_gpio_port, uint32_t cs_pin, GPIO_TypeDef* int_gpio_port, uint32_t int_pin);
```

## Documentation

The ST25R3911B datasheet is available at  
https://www.st.com/en/nfc/st25r3911b.html

