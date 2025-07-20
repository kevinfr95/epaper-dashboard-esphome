# Home Assistant ePaper Dashboard with ESP32 + Waveshare 7.5"

This project contains an [ESPHome](https://esphome.io/) configuration file that powers a battery-operated **ePaper dashboard** using a **Waveshare 7.5" display** and an **ESP32**. The display shows weather, room temperatures, battery level, energy consumption, to-do list, calendar, and EV charging status — all updated from your Home Assistant instance.


## Full  Guide

Follow the **step-by-step tutorial** to build the complete device (hardware + software + 3D printed case ):

 [Full Tutorial](https://tech-my-mind.com/posts/tutos/photoframe-epaper-dashboard/) 

---

## ⚠️ Important Notice

The provided ESPHome YAML contains **anonymized sensor values** (e.g., temperature sensors, text sensors, calendar, EV status).  
👉 **You must replace those `sensor:` and `text_sensor:` `entity_id`s** with the ones matching your own Home Assistant setup.

Example:

```yaml
# Replace this...
entity_id: sensor.temp_room1

# With your real sensor, e.g.:
entity_id: sensor.living_room_temperature
