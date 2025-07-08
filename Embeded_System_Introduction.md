### Embedded Systems Introduction

#### What is YOCTO?
- To build your own Linux OS.

---

### 1. What is an Embedded System?
An *Embedded System* is a combination of *computer hardware and software* designed to perform a *specific function* or set of functions.

#### Key Characteristics of Embedded Systems:
- Contains a *processing unit*  
- Includes *temporary memory (RAM)* and *permanent storage (Flash, ROM)*  
- *Customized* for specific applications  
- *Low cost* compared to general-purpose computers  

---

### 2. Real-life Example: Smartphone
A smartphone is a complex system with multiple embedded components. Each component can be considered an embedded system in itself.

---

### 3. Software Perspective: Security System Example

#### Option 1: General-Purpose Computer
- Attach a camera and develop an intruder detection app.
- *Pros:* Easy and fast to develop  
- *Cons:* Expensive (e.g., ₹100,000 for PC + ₹3,500 camera), unnecessary features like display, keyboard, etc.

#### Option 2: Raspberry Pi (General-Purpose Embedded Board)
- Attach a camera and write custom software.
- *Cost:*  
  ₹4,000 (Raspberry Pi) + ₹3,500 (camera) + ₹1,000 (Wi-Fi) ≈ ₹6,500  
- *Still not optimal:*  
  Includes unused hardware like:  
  - HDMI port & controller  
  - USB ports & controllers  
  - Ethernet port & controller

#### Option 3: Custom Embedded System
- Based on Raspberry Pi design, a *hardware engineer* builds a custom PCB:  
  - Removes HDMI, Ethernet, USB, etc.  
  - Adds *only essential components* like a Wi-Fi module  
- *Embedded software engineers* write software to handle alert functionality  
- *Cost:* ₹1,000 (custom board) + ₹3,500 (camera)

---

### 4. Where Are Embedded Systems Found?
- TVs  
- Home Appliances  
- Gaming Consoles  
- Automobiles  
- Medical Devices  
- Industrial Robots  

---

### 5. Advantages and Disadvantages

#### ✅ Pros:
- Cost-efficient  
- Purpose-built for specific tasks  
- Optimized performance and user experience  

#### ❌ Cons:
- *Hardware constraints* (limited RAM, CPU, I/O)  
- *Longer development time* compared to PCs  

---

### 6. Desktop Linux vs Embedded Linux

| Feature              | 🖥 Desktop Linux                            | ⚙ Embedded Linux                            |
|----------------------|----------------------------------------------|----------------------------------------------|
| Hardware             | General-purpose (laptops, desktops)          | Custom-designed (e.g., Raspberry Pi board)    |
| Focus                | Software customization                       | Board customization                          |
| Use-case             | Install apps like browsers, IDEs             | Choose CPU, RAM, I/O per use-case            |
| GUI Environment      | Full GUI (GNOME, KDE)                        | CLI or lightweight GUI (Qt, GTK)             |
| Hardware Support     | Rich (keyboard, display, Wi-Fi)              | Minimal, only needed components              |
| Optimization         | Software-level                               | Power, performance, and size                 |
| Key Point            | You *don’t change hardware, change software | You **design/modify hardware* to match software |
