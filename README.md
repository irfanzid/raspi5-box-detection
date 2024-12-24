# Box Detection with RASPI5 and PI AI Camera
## Raspi5 pinout
![raspi5 pinout](raspi5Pinout.png)

## Change ssid and password use sd card
### Example
```
    ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev
    update_config=1
    country=id

    network={
        ssid="ZHORDAN2"
        psk="takonandi"
        key_mgmt=WPA-PSK
    }
```