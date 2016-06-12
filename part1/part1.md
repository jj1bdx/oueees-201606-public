footer: Kenji Rikitake / oueees 201606 part 1 14-JUN-2016
slidenumbers: true

# oueees-201606 Part 1: IoT device technologies

<!-- Use Deckset 1.4, Next theme, 4:3 aspect ratio -->

---

# Kenji Rikitake

14-JUN-2016
School of Engineering Science
Osaka University
Toyonaka, Osaka, Japan
@jj1bdx

---

# Lecture notes on GitHub

* [https://github.com/jj1bdx/oueees-201606-public/](https://github.com/jj1bdx/oueees-201606-public/)
* Don't forget to *check out the issues*!

---

# IoT = electronics

---

# Trends in IoT devices

* They are *computers*
* Small, less physical constraints
* Less power, voltage, and heat
* Driven by *software*

---

# Legacy parts

![inline](part1-circuits-annotated.jpg)

---

![right](Motherboard_diagram.svg.jpg)

# Traditional PC

* Motherboard[^1]
* CPU
* Memory
* "Peripherals"
* Video
* Extension bus

[^1]: [Diagram by Moxfyre](https://commons.wikimedia.org/wiki/File:Motherboard_diagram.svg), [CC BY-SA-3.0](http://creativecommons.org/licenses/by-sa/3.0/)

<!-- <a href="//en.wikipedia.org/wiki/User:Moxfyre" class="extiw" title="wikipedia:User:Moxfyre">Moxfyre</a> at <a href="//en.wikipedia.org/wiki/" class="extiw" title="wikipedia:">English Wikipedia</a> [<a href="http://www.gnu.org/copyleft/fdl.html">GFDL</a>, <a href="http://creativecommons.org/licenses/by-sa/3.0/">CC-BY-SA-3.0</a>, <a href="http://www.gnu.org/copyleft/fdl.html">GFDL</a> or <a href="http://creativecommons.org/licenses/by-sa/2.5-2.0-1.0">CC BY-SA 2.5-2.0-1.0</a>], <a href="https://commons.wikimedia.org/wiki/File%3AMotherboard_diagram.svg">via Wikimedia Commons</a> -->

---

![fit](Intel_D945GCPE_Board.JPG)

<!-- By Julianprescott2604juuly (Own work) [<a href="http://creativecommons.org/licenses/by-sa/4.0">CC BY-SA 4.0</a>], <a href="https://commons.wikimedia.org/wiki/File%3AIntel_D945GCPE_Board.JPG">via Wikimedia Commons</a> -->

---

# Computers for IoT: microcontrollers

* All in one board or chip
* CPU + ROM + RAM
* GPIO (Digital I/O)
* Analog interface (A/D, D/A)
* Communications (USB, Serial, SPI, I2C)
* Ethernet / WiFi / Bluetooth

---

# Legacy CPUs .vs. microcontrollers

* Power consumption/management
* Built-in I/O interfaces
* Virtualization and memory protection
* Operating environment
* Features/functions

---

# Raspberry Pi

Rasberry Pi 3 Model B

![inline](Raspberry_Pi_B+_rev_1.2.svg.png)

<!-- By Efa2 (Own work) [<a href="http://creativecommons.org/licenses/by-sa/4.0">CC BY-SA 4.0</a>], <a href="https://commons.wikimedia.org/wiki/File%3ARaspberry_Pi_B%2B_rev_1.2.svg">via Wikimedia Commons</a> -->

---

![fit](Raspberry_Pi_3_Model_B.png)

<!-- By Herbfargus (Own work) [<a href="http://creativecommons.org/licenses/by-sa/4.0">CC BY-SA 4.0</a>], <a href="https://commons.wikimedia.org/wiki/File%3ARaspberry_Pi_3_Model_B.png">via Wikimedia Commons</a> -->

---

# Design and implementation of IoT products

---

# Prototyping

* Using breadboards
* No-solder wiring
* Easy but *unstable*
* Many startup projects haven't got further than this phase
* *Not* production-ready

---

![fit](Arduino2009-breadboard.jpg)

<!-- Photo by oomlout [CC BY-SA 2.0](http://creativecommons.org/licenses/by-sa/2.0), [via Wikimedia Commons](https://commons.wikimedia.org/wiki/File%3ABreadboard_Arduino_BBAC_-_Step_2_Programming_with_a_Duemilanove.jpg) -->

---

# Building actual products

* Soldering surface-mount chips and parts
* Making *small as possible*
* Factory built
* Minimalize the features
* Physically and electronically stable
* Legally approved (FCC/UL, CE, PSE)

---

![fit](Picoduino.png)

<!-- Photo by Bobricius (Own work) [CC BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0), [via Wikimedia Commons](https://commons.wikimedia.org/wiki/File%3APicoduino_size_demonstration.png) -->

---

# Other issues

* Mechanical alignment and stability
* Long-term reliability
* Product life cycle determination
* Vulnerability assessment
* Security and privacy
* Legal liability

---

# Real-world interface: sensors

---

# What are sensors?

Converting environmental changes into information output

---

### Wikimedia Commons credits for photos


```markdown
<https://commons.wikimedia.org/wiki/File%3AMotherboard_diagram.svg>
<https://commons.wikimedia.org/wiki/File%3AIntel_D945GCPE_Board.JPG>
<https://commons.wikimedia.org/wiki/File%3ARaspberry_Pi_B%2B_rev_1.2.svg>
<https://commons.wikimedia.org/wiki/File%3ARaspberry_Pi_3_Model_B.png>
<https://commons.wikimedia.org/wiki/File%3ABreadboard_Arduino_BBAC_-_Step_2_Programming_with_a_Duemilanove.jpg>
<https://commons.wikimedia.org/wiki/File%3APicoduino_size_demonstration.png>

(Licensed CC BY-SA)
```
