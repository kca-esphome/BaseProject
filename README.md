# BaseProject  <!-- omit in toc -->

This project serves as a skeleton to combine different ESPHome configurations. 

# Content <!-- omit in toc -->

- [Overview](#overview)
- [Description](#description)
  - [Prepare required software](#prepare-required-software)
    - [Create secrets file](#create-secrets-file)


# Overview

This project serves as a skeleton to combine different ESPHome configurations.

# Description

The project is structured in such a way that it can be easily integrated into the Docker workflow.

## Prepare required software

### Create secrets file

The project requires the following secrets.

**WIFI Connection**
wlan_ssid
wlan_pass

**Over-the-Air connection**
ota_id
ota_pass
ota_key

Note: wifi.yaml must be called with following parameter set
wlan_ssid_ap
wlan_pass_ap


