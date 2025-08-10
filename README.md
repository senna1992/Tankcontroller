This project aims to provide an controller for my freshwatertank build upon off the shelf parts.

What it does as of now:

1) Basic Control [on-off] over Airation, Co2-Supply, Filtration, Lighting
2) Heating Parameters (preset temp, settable delta/difference)
3) Filtration Parameters (on-off)
4) Airation (on-off)
5) Lighting Parameters (on-time and off-time)
6) Water-Change Mode (disabled heater, filter,co2-valve,airpump)
7) Safety (no airpump while co2-valve is on, filter always on while heating, alarms (iE under- or overtemp)
8) Display for temperature control state (heating, waiting, defective sensor)
9) BT-Proxy for Homeassistant
10) Watchdog addon device for additional safety

Feel free to integrate new sensors (ph, tds, oxygen)! the underlying esp32s3 has got enough pins left to use!
