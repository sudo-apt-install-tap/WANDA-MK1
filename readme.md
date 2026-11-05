 <div align="center">

<h1>
  <b>WANDA mk1</b>
</h1>

<h3><b>Wireless Anti Network Device Adaptive</b></h3>

<h3>A compact ESP32-C3 based RF hardware experimentation platform!</h3>

</div>

## **Overview**

WANDA mk1 is a custom-designed PCB built around an ESP32-C3 Super Mini, featuring an OLED display, three control buttons and two NRF24 modules.

The project was designed in EasyEDA, with a custom PCB and 3D-printed enclosure.

### Why?

Well, I've made WANDA once before, although that was on a breadboard. It worked remarkably well as a prototype, but I wanted something a little more permanent.

Also, I wanted to experiment with PCB design, RF hardware, power stability and enclosure design.

And honestly, making a proper PCB is much more satisfying than having wires hanging everywhere.

### Features

1. ESP32-C3 Super Mini based.
2. 0.96" OLED display for the interface.
3. 3 physical control buttons.
4. 2 NRF24 modules.
5. Exposed debugging and I2C headers.
6. Additional capacitors for power rail stability.
7. Custom PCB and 3D-printed enclosure.

**IMPORTANT:** This is an educational hardware project. Do not use it to intentionally interfere with wireless communications. RF jamming is illegal in many jurisdictions and can disrupt critical communications, including emergency services. This repository is not an invitation to build or operate a jammer.

## PCB

The PCB was designed in EasyEDA. The layout is relatively simple, and is actually quite similar to my previous MP3 player project.

I also added mounting holes to make integrating the board into the enclosure easier.

Unlike some of my other projects, this isn't designed to be independently portable. It requires an external power source.

## CAD

The enclosure was designed around the PCB's geometry. Exporting the PCB model from EasyEDA Standard into Professional was necessary to get the board into the CAD workflow.

Everything went pretty smoothly, which is honestly a nice change.

## Images

<div align="center">

<img width="431" height="557" alt="image" src="https://github.com/user-attachments/assets/5d7043b7-a6d7-4949-b7f6-88a02609f9a1" />


<br>PCB Design

---

<img width="966" height="557" alt="image" src="https://github.com/user-attachments/assets/fd1e087c-1242-49b0-8bcf-2cd293a14a2f" />

<br>Schematic

---

<img width="966" height="575" alt="image" src="https://github.com/user-attachments/assets/243d201d-1a04-490b-9f6b-cb63b673a5b4" />

<br>3D PCB Viewer

---

<img width="626" height="511" alt="image" src="https://github.com/user-attachments/assets/fdfb6a17-4e4f-4e4f-afa9-2a9ea16989fd" />

<br>Enclosure CAD

---

</div>

## Firmware & Credits

Something I'd like to clarify: **I DID NOT WRITE THE FIRMWARE!**

The firmware was developed by [littlehakr](https://www.youtube.com/watch?v=SI2MIFB81pw).

Definitely recommend checking out his other projects as well. His hardware experiments are pretty interesting!

The PCB design is my own work, while the firmware is independently developed by its original author.

Please refer to the original author's repository for attribution and licensing information.
