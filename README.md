# kitchen-timer-hardware-implementation
A 8-step timer for kitchen, with full hardware implementation


This design is a 8-step timer with equal division of time steps, with one 'SET' button to set the starting step and an 'OFF' button to turn it off. By pressing 'SET' button, the high logic pin of the counter 4017 changes, and then automatically goes down by spending time steps (each at 5 minutes) to the pin Q9 of 4017. At this time  a ring is heared from the speaker. The pins Q1 to Q8 are connected to LEDs with e. g. green color and the pin Q9 can be connected to an LED with different color (for example a red one). The other push button which is the 'OFF' key can take the state of 4017 to Q0, which is not connected to any LED. This hardware implementation can reduce cost down to 0.5 USD, while the cheapest microcontroller can be 2USD (like ATmega8).
