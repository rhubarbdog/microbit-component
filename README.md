<h1>Components</h1></br>

<h2>Displays</h2></br>

<h4>ht16k33, generic i2c driver for 8x8 LED Matrix</h4>
https://bitbucket.org/thesheep/microbit-ht16k33/src/tip/ht16k33.py

<h4>LCD1602, generic i2c LCD driver for 16x2 ... 40x4 screens</h4>
https://github.com/rhubarbdog/microbit-LCD-driver

<h4>tm1637, 4 digit 7 segment LED display</h4>
https://github.com/mcauser/microbit-tm1637

<h2>Temperature, Humdity and Weather</h2></br>

<h4>TMP35, TMP36 & TMP37 - Measure temperature with an analog device</h4>
The TMP36 converts between an analog voltage and degrees celcius via the
following code snippet. TMP35 and TMP37 use similar logic but have different
parameters.

The TMP36 produces 750 mV at 25°C and has an output scale factor of
10 mV/°C

```
millivolts = pin0.read_analog() * 3300 / 1023
degrees = ((millivolts - 750) / 10) + 25
```

<h4>DHT11 - digitally measure temperature and humidity</h4>
https://github.com/rhubarbdog/microbit-dht11

<h4>DHT12 - digitally measure temperature and humidity over the i2c bus</h4>
https://github.com/mcauser/microbit-dht12

<h4>AM2320 - digitally measure temperature and humidity over the i2c bus</h4>
https://github.com/mcauser/microbit-am2320

<h2>Keypads, Keyboards and Generic Input devices</h2></br>

<h4>mpr121 capacative touch keypad</h4>
https://github.com/rhubarbdog/-microbit-mpr121-keypad

<h2>Distance</h2></br>

<h4>HC-SR04 - ultrsonic range finder</h4>
https://github.com/fizban99/microbit_hcsr04
