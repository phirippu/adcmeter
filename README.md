# adcmeter
A TM1637 based metering example. STM32 samples one ADC channel and shows immediately the result on the display. Can be used as a starting point for an application using ADC or display. 

ADC is never polled, data is transferred by DMA. A flag is raised inside a DMA interrupt, which is polled in main().
