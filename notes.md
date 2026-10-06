# Learning Notes — GPIO LED

## What I learned

### GPIO

GPIO means General Purpose Input/Output.

A GPIO pin can be configured as an input or output.

### pinMode()

```c
digitalWrite(LED, HIGH);
Sets the output pin HIGH.
digitalWrite(LED, LOW);
Sets the output pin LOW.
delay(1000);
Creates a delay of 1000 milliseconds (1 second).
pinMode(LED, OUTPUT);
My Experiment
I changed the normal LED blink timing and observed how changing the delay changes the LED behaviour.
Next Concept
My next goal is to understand how GPIO control works closer to the hardware using registers and bit manipulation.
```text
Add GPIO learning notes
