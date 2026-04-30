# HwCamahack

Grab cam shots from target's phone front camera or PC webcam just sending a link.

## DEVLOPER BY HEXCA WEB 
assalamualaikum everyone this is educational purpose 

### What is hwCamahack?
hwCamahack is a technique to take cam shots of a target's phone front camera or PC webcam. hwCamahack hosts a fake website on an in-built PHP server and uses tunneling services to generate a link which we will forward to the target, which can be used over the internet. The website asks for camera permission and if the target allows it, this tool grabs camshots of the target's device.

### Features
In this tool, I added two automatic webpage templates to engage the target on the webpage to get more pictures of the cam:
* Festival Wishing
* Live YouTube TV

Simply enter the festival name or YouTube's video ID.

### This Tool Tested On:
* Kali Linux
* Termux
* MacOS
* Ubuntu
* Parrot Sec OS

---

### Installing and Requirements (Termux)

First, run the following commands step-by-step on your Termux terminal to install the required dependencies:

```bash
termux-setup-storage
pkg update -y && pkg upgrade -y
apt update && apt upgrade -y
pkg install wget curl -y
pkg install python -y
pkg install openssh -y
pkg install php -y
pkg install git -y
pkg install cloudflared -y
pip install flask
python -m pip install flask
pip install colorama
python -m pip install colorama
```

### Step 2: Clone and Run

After installing the packages, clone the repository and start the tool:

```bash
git clone [https://github.com/Hackerscolonyofficial/HCO-Cam-Tam.git]
ls
cd HCO-Cam-Tam
ls
chmod +x *
python main.py
```

---

### Video Demo
*(https://youtube.com/@hexcaweb2.0?si=osgqRo3QHtT8BtQ4)*

For More Videos subscribe to **HEXCA WEB** YouTube Channel.

**Disclaimer:** hwCamahack is created to help in penetration testing and is solely for educational purposes. The creator is not responsible for any misuse or illegal activities.

*Inspired by https://github.com/thelinuxchoice/ - Big thanks to @thelinuxchoice*
