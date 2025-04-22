# Raspberry-Pi-Robot
For our final project we decided to make a robot that will give the user a high five. We used parts like motors, sensors, speakers, and we used the many legos to build structures that will hold our build.

Our first steps included brainstorming ideas for our robot and we landed on a robot that can scan colors and do different actions.


# Raspberry Pi
<h2>Ports</h2>

<h3>Power Input (USB-C Port)</h3>

Purpose: Supplies regulated power (typically 5V/3A) to the Raspberry Pi board.

Details: Utilizes USB Power Delivery (USB-PD) for voltage negotiation. Powers the system’s components including USB hubs, HDMI, and GPIO.

<h3>USB Ports (2× USB 3.0, 2× USB 2.0)</h3>

Purpose: Enables data transfer and connectivity for peripherals like keyboards, mice, and storage devices.

Details: USB 3.0 ports provide up to 5Gbps, ideal for high-speed devices. USB 2.0 ports offer 480Mbps. All ports are backward compatible.

<h3>Ethernet Port (RJ45)</h3>

Purpose: Offers wired internet/network connectivity.

Details: Supports 10/100/1000 Mbps. On models like the Raspberry Pi 4, connected via a dedicated PCIe lane for improved network throughput.

<h3>HDMI Outputs (2× Micro HDMI Ports)</h3>

Purpose: Sends digital video and audio to displays such as monitors and TVs.

Details: Supports up to dual 4K displays (4K@30Hz) or a single 4K@60Hz display. Compliant with HDMI 2.0, including CEC and audio pass-through.

<h3>Audio/Video Jack (3.5mm TRRS)</h3>

Purpose: Provides analog stereo audio and composite video output.

Details: Requires configuration via config.txt for video output. Includes built-in DAC and low-pass filter for improved analog audio quality.

<h3>GPIO Header (40-Pin)</h3>

Purpose: Allows interfacing with external components like sensors, LEDs, and motors.

Details: Includes 26 programmable GPIOs and dedicated lines for UART, I²C, SPI, and PWM. Controlled via Python, C/C++, or shell scripting.

<h3>Camera Port (CSI - Camera Serial Interface)</h3>

Purpose: Connects official and compatible camera modules.

Details: 15-pin MIPI CSI-2 connector for high-speed, low-latency data transfer directly to the GPU, supporting cameras up to 12MP.

<h3>Display Port (DSI - Display Serial Interface)</h3>

Purpose: Connects the Raspberry Pi official touchscreen display.

Details: 15-pin MIPI DSI connector transmits high-speed display data. Allows integration of power and touch input through a single cable.

<h3>MicroSD Card Slot (Located on Underside)</h3>

Purpose: Stores the Raspberry Pi’s operating system and files.

Details: Supports UHS-I MicroSD cards. Primary boot source unless configured otherwise. Performance depends heavily on card speed and quality.


# Robot
![IMG_6354](https://github.com/user-attachments/assets/7fb62764-1c46-4a03-b7c3-5025d5778363)

![IMG_6353](https://github.com/user-attachments/assets/f6aa6a13-9cba-4165-9786-ac6e4439619c)

![IMG_6355](https://github.com/user-attachments/assets/a6c9ecb1-625b-4725-b3fc-81357f62b98f)

# Code
Our code involves a variety of things. It has simple prints and it also has more complex things like playing the music. The code also includes the commands for when the high five happens. Unfortunately, the color sensor is poor and it can not detect colors very well but it can detect a few.

![Pic1](https://github.com/user-attachments/assets/cb280240-d8d4-41d1-866e-0f1a1f6a0d9b)

![Pic2](https://github.com/user-attachments/assets/9710e8c6-bbc7-40c3-90ef-1e8f75fcf3ae)

![Pic3](https://github.com/user-attachments/assets/624ad43a-3d19-46c2-9dbd-73f374dc787a)

![Pic4](https://github.com/user-attachments/assets/7cce154c-80aa-497f-b1e0-bd818e436ec7)

![Pic5](https://github.com/user-attachments/assets/b9b4f332-58ba-4a9e-8a9d-963097806264)

![Pic6](https://github.com/user-attachments/assets/64732323-a96c-4d0c-90e6-a9dbf751224f)

![Pic7](https://github.com/user-attachments/assets/8e8415a7-f3cd-49e7-b892-3d3ac1228185)

![Pic8](https://github.com/user-attachments/assets/6b36453a-0900-4f70-83f2-42b885d3011e)

![Pic9](https://github.com/user-attachments/assets/badf8c82-2fe0-4d15-b6bb-fea1aa6ef511)

