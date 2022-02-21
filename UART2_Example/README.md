# USART2
Sets USART2  on pins PA2 and PA3. Normally this can be done throug the USB. The Pins on this board are not necessary.


use msp.c and it.c



HAL_Init(); // Must be ran first to get the HAL library



HAL_MspInit() // App specific. Low level processor specific inits.
Set priority interrupts, for memorymanagement busfault and usagefault


HAL_UART_MspInit() 	 //here we are going to do the low level inits. of the USART2 peripheral


UART2_Init()
