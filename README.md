<h1>push buttons</h1>

<p>There are many different types of buttons and they allow you to control a DC power source, by simply cutting the voltage. Push-button is the simplest type of button; the breakout uses a latching analog circuit that is triggered by a push of the button. Press once to turn on, and then press again to turn off. There are already pre-made modules that can be used with a microcontroller, however in the example below we will you normal push-button to and wire it up using breadboard.</p>

<p>The button works fine with 3V and it can go up to 14V, in this case we will use 5V from the Arduino. We also need to wire a ground, which will complete the circuit; it is safer to connect a 10K pull-down resistor between the GND and button. Also in this example we will add a signal from a button to Arduino that will be connected to a digital pin. In this case we can measure the on/off signal via the serial connection.</p>

<h2>Hardware</h2>

<p>
  
  - Arduino Uno

  - Push button
  
  - 10K resistor
  
</p>

<h2>Wiring</h2>

<p> See diagram here:
  
https://github.com/kingston-hackSpace/push-button-with-arduino/blob/main/push_button_bb.png
  
</p>

<h2>Code</h2>

<p> See Arduino code here:

https://github.com/kingston-hackSpace/push-button-with-arduino/blob/main/push_buttons.ino
  
</p>

<h2>Understanding push buttons</h2>

<p> 
</p>
