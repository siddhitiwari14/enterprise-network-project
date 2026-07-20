# Enterprise Network Project

This repository contains a basic enterprise networking lab designed to demonstrate a small routed network with supporting switch configurations and a visual topology diagram.

## Project Overview

The project includes:
- A router configuration with two subnetted interfaces
- Two switch configurations for Layer 2 access and distribution functions
- A topology diagram showing the overall network layout

## File Structure

- `README.md` – Project overview and documentation
- `configs/router-config.txt` – Router running configuration
- `configs/switch1-config.txt` – First switch running configuration
- `configs/switch2-config.txt` – Second switch running configuration
- `topology-diagram.png` – Network topology image

## Network Highlights

- Router interfaces configured with private IP ranges:
  - `192.168.40.1/25` on GigabitEthernet0/0
  - `192.168.40.129/25` on GigabitEthernet0/1


## Purpose

This project is intended for studying:
- Cisco configuration structure
- Basic router and switch setup
- Network topology documentation
- Enterprise network design fundamentals
