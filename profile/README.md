# GTS6L Development

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Samsung%20Galaxy%20Tab%20S6-14213D?style=for-the-badge&logo=samsung&logoColor=white" />
  <img src="https://img.shields.io/badge/Architecture-ARM64-334155?style=for-the-badge" />
  <img src="https://img.shields.io/badge/SoC-Qualcomm%20SM8150-2563EB?style=for-the-badge&logo=qualcomm&logoColor=white" />
  <img src="https://img.shields.io/badge/Development-Open%20Source-475569?style=for-the-badge&logo=github&logoColor=white" />
</p>

<p align="center">
  <strong>Bringing new possibilities to the Samsung Galaxy Tab S6.</strong>
  <br />
  Device development, hardware adaptation and low-level software engineering.
</p>

---

## Overview

**GTS6L Development** is an independent development initiative focused on the Samsung Galaxy Tab S6 platform.

The project aims to maintain, improve and organize device-specific software components for the Galaxy Tab S6 family, with particular attention to hardware compatibility, platform integration and reusable configurations.

Built around the Qualcomm Snapdragon 855 (SM8150) platform, this organization brings together device trees and shared components for different hardware variants.

Our goal is to make development for this hardware more accessible, maintainable and reproducible.

## Supported Devices

| Device | Model | Codename | Variant |
|---|---|---|---|
| Samsung Galaxy Tab S6 | SM-T860 | `gts6lwifi` | Wi-Fi |
| Samsung Galaxy Tab S6 LTE | SM-T865 | `gts6l` | LTE |

**Hardware platform:** Qualcomm Snapdragon 855 (SM8150)  
**Architecture:** ARM64  
**Display:** 2560 × 1600

## Repository Structure

The organization is divided into device-specific repositories and shared platform components.

### Device Trees

| Repository | Description |
|---|---|
| [android_device_samsung_gts6l](https://github.com/gts6l-devolpment/android_device_samsung_gts6l) | Device configuration for the Galaxy Tab S6 LTE (SM-T865). |
| [android_device_samsung_gts6lwifi](https://github.com/gts6l-devolpment/android_device_samsung_gts6lwifi) | Device configuration for the Galaxy Tab S6 Wi-Fi (SM-T860). |

### Common Platform

| Repository | Description |
|---|---|
| [android_device_samsung_sm8150-common](https://github.com/gts6l-devolpment/android_device_samsung_sm8150-common) | Shared configurations and hardware integration for Samsung devices based on the SM8150 platform. |

## Technical Foundation

The current public repositories contain Android device configuration components based on the Qualcomm SM8150 platform and LineageOS build infrastructure.

Key areas include:

- **Device Trees:** Hardware-specific configuration and product definitions.
- **Kernel Integration:** Device kernel configuration and platform references.
- **Display:** Resolution, density and display-related configuration.
- **Audio:** Audio platform configuration and mixer settings.
- **Sensors:** Sensor HAL configuration and hardware integration.
- **Connectivity:** Wi-Fi, Bluetooth and LTE-related configurations.
- **Input:** Touchscreen and S Pen integration.
- **VINTF:** Hardware interface manifests and compatibility configuration.
- **Recovery:** Device-specific recovery configuration.

The common platform repository helps reduce duplication and maintain consistency between the Wi-Fi and LTE variants.

## Development Philosophy

We believe device development should be:

- **Open:** Source code and technical decisions should be accessible.
- **Modular:** Shared components should remain independent from device-specific implementations.
- **Maintainable:** Configurations should be organized and documented.
- **Reproducible:** Development processes should be understandable and repeatable.
- **Community-driven:** Contributions, testing and technical feedback are welcome.

## Project Roadmap

The development process is organized around several objectives:

| Area | Objective |
|---|---|
| Device Support | Maintain configurations for SM-T860 and SM-T865. |
| Platform Integration | Improve shared SM8150 components. |
| Hardware Compatibility | Investigate and improve peripheral support. |
| Input Support | Maintain touchscreen and S Pen integration. |
| Documentation | Improve technical documentation and development guides. |
| System Development | Explore additional operating system possibilities for the platform. |

This roadmap represents development goals, not a claim that every feature is currently implemented or fully functional.

## Contributing

Contributions are welcome.

If you are interested in improving device compatibility, investigating hardware behavior, fixing configuration issues or contributing documentation, feel free to explore the repositories.

Before submitting changes:

1. Review the existing repository structure.
2. Understand the device-specific and common configurations.
3. Keep changes focused and properly documented.
4. Include relevant testing information whenever possible.

For significant changes, consider opening an issue before submitting a pull request.

## Licensing

Individual repositories may contain components with different licenses and copyright notices.

Always check the license and attribution requirements of the specific repository and files before redistributing or modifying their contents.

---

<p align="center">
  <strong>GTS6L Development</strong>
  <br />
  <sub>Independent development for the Samsung Galaxy Tab S6 platform.</sub>
  <br /><br />
  <a href="https://github.com/gts6l-devolpment">GitHub Organization</a>
</p>
