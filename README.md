# hybrid-guitar-amplifier
Hybrid guitar amplifier project for the Design Laboratory course at AGH

This amplifier consists of valve preamplifier and solid state power amplifier.

Equalizer
The schematic for the equalizer was taken from the AVT186 kit. The values of the components were changed to provide three bands for the filters: 100Hz, 800Hz and 6400Hz.

![eq board](https://user-images.githubusercontent.com/47760713/53008461-c1c1e200-3439-11e9-8a5c-bb9bcad4462f.png)

![eq schematic](https://user-images.githubusercontent.com/47760713/53008464-c1c1e200-3439-11e9-95c5-ba77b820f0c4.png)

MOSFET overdive effect
It was simple two stage amplifier to create distorted signal with a harsh clipping.

![mos board](https://user-images.githubusercontent.com/47760713/53008466-c1c1e200-3439-11e9-96d0-05ed13b1bd78.png)

![mos schematic](https://user-images.githubusercontent.com/47760713/53008467-c1c1e200-3439-11e9-8b64-0a93ef3ac955.png)

Channel select board
This board allowed to change the channels of the preamplifier and control the effects loop with 3 analog multiplexers. They were handled by the Atmega328p microcontroller. 

![mux board](https://user-images.githubusercontent.com/47760713/53008468-c25a7880-3439-11e9-9cdd-02a35862e681.png)

![mux schematic](https://user-images.githubusercontent.com/47760713/53008469-c25a7880-3439-11e9-9ddf-a0d284c251b2.png)

Power amplifier
The TDA7292 was used in the bridge tied load configuration to increase the power output in this stage.

![poweramp board](https://user-images.githubusercontent.com/47760713/53008470-c25a7880-3439-11e9-98ee-048b57bae5a0.png)

![poweramp schematic](https://user-images.githubusercontent.com/47760713/53008471-c25a7880-3439-11e9-97a6-2e03fe5c9237.png)

Valve preamplifier
This circuit was based around 12AX7 valve. The double triode provided two gain stages in order to achieve overdriven signal.

![preamp board](https://user-images.githubusercontent.com/47760713/53008472-c2f30f00-3439-11e9-826f-34c2d98220c4.png)

![preamp schematic](https://user-images.githubusercontent.com/47760713/53008473-c2f30f00-3439-11e9-89d0-1226b93b6177.png)
