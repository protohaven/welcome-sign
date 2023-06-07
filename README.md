# Protohaven "Makers Welcome" Sign

The "Makers Welcome" sign was created in June of 2023 as part of a catalyst connection boot camp.  Students did metalwork to cut out the
letters and affixed them to an armiture. Then the students did the electronics work to add lights that are controlled by a motion sensor.

The sign in the entry way of Protohaven is powered by a Raspberry Pi Pico W running Micropython and this repo is to
allow members to improve and enhance what the sign does.

## Details
- The micronctroller is a Raspberry Pi Pico W running Micropython.
- There is a string of xx neopixels on pin 4 the first xx are back lighting the top part and the remainder edge light the bottom part.
- There is a PIR senson on pin 16.
