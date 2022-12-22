# Bluetooth examples for GSDK 4.2.0

## Bluetooth - SoC Basic

- The Bluetooth - SoC Basic example is a project that you can use as a template for any standalone Bluetooth application
- This example requires a Gecko Bootloader with Apploader, same as the default SoC Empty, 
- Start address 0x00012000
- Otherwise the same application as the default Bluetooth - SoC Empty but:
  - Added
    - IO Stream: USART
    - IO Stream: Retarget STDIO
    - Third Party -> Tiny printf
    - Application -> Utility -> Log
    - Board Control -> Configure -> General -> Enable Virtual COM UART -> Enabled

## Bluetooth - SoC Basic without Bootloader support

- The Bluetooth - SoC Basic example is a project that you can use as a template for any standalone Bluetooth application
- This example is a special application that does not need any bootloaders
- Start address 0x00000000
- Otherwise the same application as the default Bluetooth - SoC Empty but:
  - Added
    - IO Stream: USART
    - IO Stream: Retarget STDIO
    - Third Party -> Tiny printf
    - Application -> Utility -> Log
    - Board Control -> Configure -> General -> Enable Virtual COM UART -> Enabled
  - Removed
    - In-Place OTA DFU
    - Bootloader Application Interface (App Properties is automatically removed)

## Bluetooth - SoC Empty for Bootloader with Apploader

- The Bluetooth - SoC Empty for Bootloader with Apploader example is a project that you can use as a template for any standalone Bluetooth application
- This example requires a Gecko Bootloader with Apploader.
- Start address 0x00012000
- The same application as the default Bluetooth - SoC Empty

## Bluetooth - SoC Empty for Bootloader without Apploader

- The Bluetooth - SoC Empty for Bootloader without Apploader example is a project that you can use as a template for any standalone Bluetooth application
- This example requires a Gecko Bootloader that has no Apploader included
- Start address 0x00006000
- Otherwise the same application as the default Bluetooth - SoC Empty

## Bluetooth - SoC Empty without Bootloader support

- The Bluetooth - SoC Empty for without Bootloader example is a project that you can use as a template for any standalone Bluetooth application.
- This example is a special application that does not need any bootloaders
- Start address 0x00000000
- Otherwise the same application as the default Bluetooth - SoC Empty

