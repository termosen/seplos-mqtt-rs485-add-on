Hardcoded 19200 baud rate for standard Seplos wiring via RS485.
If your set up works with Seplos battery monitor software this will probably too.

Set your number of packs and USB path in configuration.

It reads every 2 seconds from the pack when battery is active and sends to the MQTT broker, when IDLE it reads every 10 seconds and sends to the MQTT broker every 5 mintues.
