# pldSCHWIM
A implementation of DosFox's Shim-IWM (Or "SCHWIM") In a single 16V8 PLD
This provides just enough hardware to pass the initial boot time hardware checks to get a mac to boot with no IWM / SWIM installed, it dose not actually emulate the IWM so the floppy drive will not function but is a good way to get a mac with a damaged IWM / SWIM up and running without having to cannibalise another board

I did not design this - I only translated it to a 16V8 type PLD. The cleaver work to make this possible was done by DosFox and Matt Evans
A full write up of how this works can be found on DosFox's GitHub - https://github.com/DosFox1/Shim-IWM

These boards have been tested on a Mac Plus, SE FDHD and a LCII and will likely work with any mac with a IWM of SWIM
These should work with most GAL/PALCE/ATF16V8 PLD's. Speed is not important, I have built these with both 15ns ATF16V8B's and 25ns PALCE16V8H's and they will likely work with any PLD in this family. The design has not been tested with 16V8C type PLD's
