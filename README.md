# pi-adhoc-mqtt-cluster
Using batman-adv to connect several raspberrypi to a mesh network and creating a vernemq cluster

## Overview

This repo is currently in development and things get added time after time.   
Feel free to comment.  

## Used hardware and software

* Raspberry Pi 3 B+
    * batman mesh node (adhoc network wlan0)
    * bridge with lan cable eth0 for combining mesh and different network
    * internet gateway with dhcp server for sharing eth0 internet with mesh nodes
    * mqtt broker cluster node with vernemq
    * grafana/prometheus/influxdb for monitoring mqtt cluster and network (not written yet)
    * Optional: USB Wifi Dongle for wifi client+hotspot configuration and internet sharing
* several Raspberry Pi Zero W (batman mesh node)
    * batman mesh node (adhoc network wlan0)
    * mqtt broker cluster node with vernemq
    
* OS: Raspbian Stretch Lite (2018-04-18-raspbian-stretch-lite.img)

## PiPages for shortcuts to the different GUIs (when already installed):

[**PiPages (Link)**](https://suiluj.github.io/pi-adhoc-mqtt-cluster/pipages/)

## Links to the tutorials:

Links to different parts:

* [Batman-adv and Batctl](https://github.com/suiluj/pi-adhoc-mqtt-cluster/wiki/Batman-Adv-and-Batctl)
* [USB Dongle - Wifi Client+Hotspot](https://github.com/suiluj/pi-adhoc-mqtt-cluster/wiki/USB-Dongle-Wifi-Configuration)
* [Prometheus](https://github.com/suiluj/pi-adhoc-mqtt-cluster/wiki/Prometheus)
* [InfluxDB](https://github.com/suiluj/pi-adhoc-mqtt-cluster/wiki/InfluxDB)
* [VerneMQ](https://github.com/suiluj/pi-adhoc-mqtt-cluster/wiki/VerneMQ)
* [Grafana](https://github.com/suiluj/pi-adhoc-mqtt-cluster/wiki/Grafana)
* [Node-RED install on raspberrypi for testing](https://nodered.org/docs/hardware/raspberrypi)
