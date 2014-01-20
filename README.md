# Virtual Reality with PIANO

I've created a simple virtual piano. I've connected my HMD, an Oculus Rift DK1, and managed to get it working, as I'm playing the piano!

You can see a proof of concept of this in 2 videos that I've made :

https://mediacru.sh/Yq0rz71QrqN2

https://mediacru.sh/6GWSihSKZ7u9 (no sound for this one since I didn't have my microphone this time... but it's working!)


## Tools

Everything is done thanks to Blender, an open source graphics program. All is done with a linux PC (ubuntu 13.10)

Different modules are needed to make it work :

  -To connect my Oculus Rift to Blender : I've used an open source program : OpenHMD ( https://github.com/OpenHMD/OpenHMD )
  
  -to connnect my Piano to the PC : I've used an open source program : rtMIDI ( https://pypi.python.org/pypi/python-rtmidi#downloads )
  

## Installation

You can use the Blender file inside the repository: run it inside Blender since I didn't make an autonomous program (but it could be done in the future).

I've set the program to work with my piano on a specific port of the PC (port "24", and name "ProdipeMIDIlilo"). So if your Piano doesn't use this port and this specific USB transmitter, you have to edit inside rtMIDI module the file 'midiutils.py'

### Future progress
I'm very excited with the possibilities of this! A better piano with better graphics, better virtual environment! Everything is possible! 

