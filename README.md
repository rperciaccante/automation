# automation
Home Automation Projects

This repo contains projects I have worked on related to home/RV automation interests.

Generic Components/ - Components I have put together for various uses
- esphome_secure_base_config.yaml
  This is a base configuration for ESPHome based projects with a focus
  on being secure by default and easy to modify.  

Home Automation/ - Devices I have configured for my home automation system
- Garage Door Controllers
  There are 2, one is a single garage door, and the other is two doors, plus
  environmental monitoring with a BME680 sensor.  YAML files written to be 
  compiled with ESPHome, and uses various hardware components

RV Automation/ - Contains configurations for projects used in my RV
- RV Water Controller
  Unfortunately, this is a project I needed, more than wanted.  I experienced
  a leaky water control panel in my RV that caused significant damage to the
  wood flooring.  This project buids a device that monitors for the presence
  of water or excessive humidity and shuts off a water valve and triggers an
  alert.  Conditions and alarm state are displayed on an LCD panel.

- LightControl/
  These are Shelly 1 devices flashed with ESPHome to control 12v lights
  in the RV and still allow the use of the physical switches.  They then
  become part of the Home Assistant integration,and can be triggered based 
  on time, presence, alarm state, etc.