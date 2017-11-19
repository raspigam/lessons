# Lessons: Introduction to the Raspberry Pi

This introductory course presents the Raspberry Pi computer to pupils of age 10-15.

Sources:
* https://www.raspberrypi.org/education/magpi-educators-edition
* https://www.raspberrypi.org/picademy

PDFs:
- https://raspberrypi.org/magpi-issues/MagPi49.pdf
- https://www.tes.com/teaching-resource/getting-started-with-raspberry-pi-11146710


## Things nice to mention or cover in the lessons

### What kind of computer is a Raspberry Pi

* It is a general purpose computing device, similar to a "normal" desktop PC
* It can run a number of operating systems, but most often runs Linux
* Linux is the most used operating system, maybe surprisingly, but obvious when you consider that most internet servers and
  mobile phones run a variant of Linux (e.g. Ubuntu Linux and Google's Android)
* The Raspberry Pi computer shares traits of the desktop computer but is actually comparable to the main computing board of
  a tablet computer or smart phone, while it also is extensible (easily connect custom hardware to it) and embeddable like
  smaller microcontroller-based computing devices, offering various automation solutions in consumer and industrial settings

### How is the Pi similar but also different to a "normal" desktop PC

* Although it typically runs an operating system also used for desktop computers, to execute applications the main computing
  chip ("processor") on the Raspberry Pi uses a different set of instructions from what a normal desktop computer uses. Its
  processor really is of the kind used in smart phones, tablets as well as e.g. network attached storage (NAS) and TV set 
  top box devices. The main advantage of this is that it pairs a decent overall performance and good video playing
  capabilities with very low power requirements.

### Demonstrating the capabilities of the Raspberry Pi

When using the Raspbian operating system on the Pi you can find a set of demonstration programs which can be run from the
terminal prompt.

* Open a terminal (in the top left Raspbian main menu, select `Accessories` and then `Terminal`)
* Go to the demonstration programs directory by typing `cd /opt/vc/src/hello_pi` (and hit the `enter` key)
* Type `./rebuild.sh` (and hit enter) to have all programs built ("compiled" as they say) - a lot of text will scroll by
* Type `ls` (+enter) to inspect what demos are available
* E.g. there is a video demonstration, showing that the Pi is capable of displaying smooth full HD video; you can run this
  demo by typing `cd hello_video` (+enter) to go into the video demo directory and `./hello_video.bin test.h264` (+enter) to
  play the test video provided (15 seconds of an animation called Big Buck Bunny)
* Any demonstration can be stopped by pressing `ctrl-c`
* After viewing you can return to the other demos by typing `cd ..` (+enter) and typing another `cd` but then with the name
  of an other demo you'd like to see (e.g. `cd hello_teapot` to go into the directory of the 3D teapot demonstration and
  executing `./hello_teapot.bin` )
* Remember to use `cd ..` to go back into the main demonstrations folder!

https://www.raspberrypi.org/documentation/usage/demos/README.md
