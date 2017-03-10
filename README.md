# Arbritary-Waveform-Generator-AWG-
AWG is a digital synthesis method  of generating waveforms using digital memory contents. Here it uses FPGA memory to hold "Hello" which is 
then passed into gain or volume module and then pdm which is low pass filtered to the audio output of the Nexys 4 board.

-Memory is loaded with digital 12 bit "Hello " audio
- Address counter is run to output the memory
-Rate counter to control frequency / Derived clock
-Output from memory multiplied with volume level (gain)
-It is coded into Pulse Density Modulation (PDM)
- pdm is given to headphone jack of nexys4 board to hear "hello"

-Plays with central button 
-volume to switches
