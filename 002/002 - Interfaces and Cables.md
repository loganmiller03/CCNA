# [Day 2 - Interfaces and Cables](https://www.youtube.com/watch?v=ieTH5lVhNaY&list=PLxbwE86jKRgMpuZuLBivzlM8s2Dk5lXBQ&index=4)

* RJ-45
  * image
  * used for Ethernet
* What is Ethernet
  * Ethernet is a collection of network protocols/standards
  * this lesson focuses on types of cabling as defined by Ethernet standards
* Bits and Bytes
  * 0s and 1s
  * 8 bits = 1 bytes
  * Speed is measures in bits per second(Kbps, Mbps, Gbps) not bytes
  * 1 kilobit = 1000 bits
  * 1 megabit = 1,000,000 bits
  * 1 gigabit = 1,000,000,000 bits
  * 1 terabit = 1,000,000,000,000 bits
  * petabytes, exabits, zettabits, yottabits...
* Ethernet standards
  * IEEE 802.3 standard
  * ![utp cables](002/copperethstandards.png)
* UTP Cables
  * Unshielded Twisted Pair
  * no metallic shield making them vulnerable to interference
  * twisted pair protects against EMI(Electromagnetic Interference)
  * ![utp cables](002/UTPcablesdiagram.png)
 
* Auto MDI-X eliminates the issue of straight through vs crossover cables as it can detect which pins a device trasmits and receives data on

* Fiber optics
  * SFP Transceiver (Small Form Factor Pluggable) connects to fiber optic cables
  * ![utp cables](002/fiberoptics.png)
  * ![utp cables](002/fiberopticstandards.png)
  * multimode fiber
    * core diameter is wider than single mode fiber
    * allows multiple angles(modes) of light waves to enter the fiberglass core
    * allows longer cables than UTP, but less than single mode fiber
    * cheaper than single mode fiber due to cheaper LED based SFP transmitters
  * single mode fiber
    * naarrower than multimode
    * light enters at a singe angle(mode) from a laser based transmitter
    * longer cables than UTP and multimode fiber
    * more expensive than multimode fiber
  * UTP vs fiber optic cables
    * ![utp cables](002/utpvsfiber.png)
