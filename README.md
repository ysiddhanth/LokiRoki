# LokiRoki


> [!NOTE]
> ## Project Status
>
> ### PCB Build
> - Fabrication completed
> - Components still need to be sent to the assembly company
>
> ### 3D Modeling
> - Initial work has begun
> - Files have not yet been uploaded
>
> ### Programming
> - Awaiting procurement of LoRa modules
> - Firmware testing to begin after hardware arrives

## Application / Problem Statement

Conventional walkie-talkies operate over licensed FM/VHF/UHF bands, which are subject to regulatory constraints, interference from other users, and limited range in urban environments. They are also typically bulky and expensive.

At the same time, consumer-grade Bluetooth and Wi-Fi radios offer only short-range communication and usually require existing infrastructure.

There exists a clear need for a low-cost, long-range, license-free voice communication device suitable for scenarios such as:

- Outdoor activities (hiking, camping, field operations) where cellular coverage is unavailable.
- Campus or community communications without reliance on mobile networks.
- Emergency or off-grid communication links requiring robust, low-power operation.

The proposed device targets ranges of:

- **2–5 km** in urban areas
- **Up to 15 km** in open terrain

The system operates entirely within the **license-exempt 865–868 MHz band in India**.

---

## Proposed Solution

The solution is a self-contained, push-to-talk (PTT) walkie-talkie based on the **LoRa (Long Range)** radio protocol, with onboard speech compression using **Codec 2**.

Two identical units will be built, each capable of:

- Transmitting voice
- Receiving voice
- Operating independently without cellular or internet infrastructure

---
