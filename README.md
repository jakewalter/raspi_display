# raspi_display

Setup for a Raspberry Pi connected to a geophone with an ADS1115 hat or other ADS1115 breakout board. The Raspberry Pi will run a seedlink server and the idea is to have the waveforms displayed by connecting to the seedlink server on the Pi.

## 1. Attach and connect the geophone

Enable SPI and I2C under raspi-config
Assume you are the "pi" user so that the home folder is /home/pi

```
git clone https://github.com/iris-edu/ringserver.git
cd ringserver
make
```

```
git clone https://github.com/jakewalter/raspi_display.git
cd raspi_display
```


