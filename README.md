# Home Assistant Blueprints
Blueprints to use and share

Work in progress.  Some blueprints I authored or tweaked, maybe you will find them useful.

#### Lutron related, using the [lutron_caseta](https://www.home-assistant.io/integrations/lutron_caseta/) integration.  I have only tested against a RadioRA3 controller.

* [Blueprint for Sunnata Keypads](automation/lutron-sunnata-keypad.yaml).
    Usually useful when the Lutron system controls some of the action, and you want HA to also do things based on key presses.  Leaves the button LEDs to Lutron to control.
    
    [![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Frobchandhok%2Fhomeassistant-blueprints%2Fblob%2Fmain%2Fautomation%2Flutron-sunnata-keypad.yaml)

* [Blueprint for Sunnata Keypads with LED Control](automation/lutron-sunnata-keypad-and-leds.yaml).
    Usually useful when the Lutron system controls *none* of the action, and you want HA to do all the things based on key presses.  Lights up the LED of the last button pressed.
    
    [![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Frobchandhok%2Fhomeassistant-blueprints%2Fblob%2Fmain%2Fautomation%2Flutron-sunnata-keypad-and-leds.yaml)

* [Blueprint for Pico 4 button 2 Group Keypads](automation/lutron-caseta-pico-2-group-remote.yaml).
    Catch button events from the Pico controllers that are meant to control on/off for two devices.
    
    [![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Frobchandhok%2Fhomeassistant-blueprints%2Fblob%2Fmain%2Fautomation%2Flutron-caseta-pico-2-group-remote.yaml)


-- fin --
