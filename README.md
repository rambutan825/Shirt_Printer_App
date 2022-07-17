# Shirt Printer

This repository is for converting, encoding and importing a PNG image into a RecRoom invention (`Shirt Printer - Dorm`).\
Said invention only works in your **Dorm Room** because of the **Shirt Customizer**.

If you're experiencing any mayor problems, message me on Discord: [**McRen#2940**](https://discordapp.com/users/236809680947511297/)

## How to use 

> **ONLY 16:9 screen ratio supported**\
> *If you're not sure about your screen ratio, run the script - It'll warn you if your monitor isn't supported*\
> If you really want to import, yet you don't have the acceptable screen ratio, got to `Setting -> System -> Display` 
> and change your `Display resolution` to `1920 x 1080`

## 
The invention takes a lot of ink, thus you will need to delete everythin in your dorm room. Don't worry, you can always load the last save of the room in your watch;\
`This Room` -> press the "_round arrow_" button left of the `Save Room` button.

https://user-images.githubusercontent.com/76653181/179421434-a57c714e-b90f-4bf7-a618-e6614ed1c789.mp4

##
When spawning the invention you must spawn it from your watch and not your makerpen.

![SpawnInvention](https://user-images.githubusercontent.com/76653181/179421897-ecddd84d-d33b-4b5d-aa27-9e1b5735ebed.png)


##
Run `Shirt-Printer.py`.

In the newly opened window, open a PNG image you want to print.\
I suggest the image is already converted into a RecRoom color palette 
(Photoshop ACO swatch files are included), and scaled to the appropriate size.\
If the image is not converted it will automatically get converted and dithered.

## 
After the data has been encoded, you will be prompted to import all data to RecRoom.\
For this you'll have to **Configure** the `String Variable`. You will have to **replace** the existing one with a new one (see video below)\
When you see the white `Value` input field, enter `y` in the script, tab back into RecRoom and _wait_

https://user-images.githubusercontent.com/76653181/179419753-4981f9bb-0b66-47bb-8796-cbedddf5ef56.mp4

## 
When the importing process is finished, you will have to spawn in your **Shirt Customizer**.\
The placement is very important! If the canvas is not flush with the wall the print might not work at all.
Spawn the shirt customizer, grab it and push it into the corner _as shown in the video_.

https://user-images.githubusercontent.com/76653181/179420703-911f9aff-a5a3-432a-934f-2ab1b35848b0.mp4

![ShrtCutomizerInTheCorner](https://user-images.githubusercontent.com/76653181/179421185-9eff3a75-6e41-43d8-a1ca-a811894f8304.png)

## 
Next step is the circuit board named `Shirt Printer`.\
You will have to change those inputs to suit your imported image;
* `Front And Back` - Set this to `True` if you're printing bothsided, set it to `False` if you're printing only one side.
* `Variable Import` - If you're importing the image always keep this to `True`. You only set it to `False` if you request me to import an image and let you print it (comes with a fee)
* `Main Delay` - Controls the speed of the system; if the number is too low you may experience "ghost pixels" (white dots), If so, increase the delay.
* `Image Width` - The most important one of them all; enter the same number as the width of the image you imported. if it's off even by one it **will mess up**
* `Image Height` - not as important as width; it only affects the progress display

![ShirtPrinterCircuitboardInputs](https://user-images.githubusercontent.com/76653181/179420840-0fd58e89-7a05-41b3-a81f-efd2e614c3dc.png)

##
Incase you're curious, these are all of the markers. It's best you dont touch/move them. 

![MessyMarkers-NoTouch](https://user-images.githubusercontent.com/76653181/179421202-e1e768c5-be79-4bd1-b5ba-00e6c880b162.png)


#
If you have any problems with the scripts, the invention or anything else, you can contact me on:
- [Discord: **McRen#2940**](https://discordapp.com/users/236809680947511297/)
- [RecRoom: **@McReny**](https://rec.net/user/McReny)
