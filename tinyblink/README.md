# Tinyblink

- Board: [STM32F407xx-DISCOVERY](https://www.st.com/resource/en/data_brief/stm32f4discovery.pdf)
- MCU: [STM32F407VGT6](https://www.st.com/resource/en/datasheet/stm32f405rg.pdf)
- Library: STM32Cube_FW_F4_V1.25.0

## Configuration

- GPIO of port D:
    - PD12 -> LD4 [Green LED]
    - PD13 -> LD3 [Orange LED]
    - PD14 -> LD5 [Red LED]
    - PD15 -> LD6 [Blue LED]

## Compiling/Flashing

Build with:
```
make
```

Flash with:
```
st-flash write build/tinyblink.bin 0x8000000
```
