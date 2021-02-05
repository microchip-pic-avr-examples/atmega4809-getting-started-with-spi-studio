[![MCHP](images/microchip.png)](https://www.microchip.com)

# Getting Started with Serial Peripheral Interface (SPI) Examples (Microchip Studio)

  This repository contains examples of bare metal source code for Serial Peripheral Interface (SPI) as described in [TB3215-Getting Started with Serial Peripheral Interface (SPI)](https://ww1.microchip.com/downloads/en/AppNotes/TB3215-Getting-Started-with-SPI-90003215A.pdf) document from Microchip. The repository contains a Microchip Studio Solution with multiple projects inside:

  * [<strong>Sending Data as Host:</strong>](Sending_Data_as_Host) This example demonstrates how to configure the device in SPI Host mode and send dummy data (value 0) (for more details, see [<strong>Sending Data as Host</strong>](Sending_Data_as_Host)).
  * [<strong>Changing Data Transfer Type:</strong>](Changing_Data_Transfer_Type) This example demonstrates how to configure the device in SPI Host mode and to send data with respect to the clock polarity and the clock phase, in data mode 3 (for more details, see [<strong>Changing Data Transfer Type</strong>](Changing_Data_Transfer_Type)).
  * [<strong>Receiving Data as Client:</strong>](Receiving_Data_as_Client) This example illustrates how to configure the device in SPI Client mode and how to receive data from an SPI host device, using the SPI interrupt (for more details, see [<strong>Receiving Data as Client</strong>](Receiving_Data_as_Client)).

## Related Documentation
More details and code examples on the ATMEGA4809 can be found at the following links:
- [TB3215-Getting Started with Serial Peripheral Interface (SPI)](https://ww1.microchip.com/downloads/en/AppNotes/TB3215-Getting-Started-with-SPI-90003215A.pdf)
- [ATMEGA4809 Product Page](https://www.microchip.com/wwwproducts/en/ATMEGA4809)
- [ATMEGA4809 Code Examples on GitHub](https://github.com/microchip-pic-avr-examples?q=atmega4809)
- [ATMEGA4809 Project Examples in START](https://start.atmel.com/#examples/ATMEGA4809XplainedPro)


## Software Used
- Microchip Studio 7.0.2542 or newer [(https://www.microchip.com/mplab/microchip-studio)](https://www.microchip.com/mplab/microchip-studio)
- ATmega_DFP 1.6.364 or newer Device Pack


## Hardware Used
- ATMEGA4809 Xplained Pro [(ATMEGA4809-XPRO)](https://www.microchip.com/developmenttools/ProductDetails/ATMEGA4809-XPRO)
