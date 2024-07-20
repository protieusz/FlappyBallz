# FlappyBallz
**FlappyBallz**, a variant mod of the famous Eek custom keyboard by **Klackygears**. 90 degrees, 36 keys angled layout with a 25mm trackball. Thanks to **HA HA HA** of 40's Discord channel for the chosen name.

# Description
**FlappyBallz** was blessed by **Klackgears** who originally designed the EEK! Here are the list of heavy mods done to the orignal design:

-PCB outline was extracted from combined Kicad PCB file and DXF files from **Klackgears'** respository. PCB is powered by RP2040 CORE-A mcu smd soldered.  USB C port along with the 5.1K resistors, ESD and a fuse is position at the Eek moutpiece area.  PCB is not ground copper fill in order to facilitate easier hot plate solder and or if needed hand soldering.  PCB is ordered from JLCPCB (July 19, 2024) and I will do my own PCBA on a hot plate. As always my PCB designs are all done on EasyEDA.

-Eek silkscreen better version was provided by **Klackgears** and was used for the top and bottom silkscreen on the PCB. The head and body of the Eek silkscreen was also use to extrude so that it looks 3D on the case design.

-PMW3360 sensor footprint is added to the center ish of the head area below the mouth.

-No switch plate was created because I was not able to accurately align the square holes properly. Kicad DXF extract file was not too helpful as it constantly crashes if I tried to edit it in Fusion360

-A full case was designed and created from whatever files in Klackygears's repository. 

-Top, bottom case & PCB were held together by a couple of M2 screens with brass hot inserts 3.2mm in diameter. I haven't tested out the brass hot inserts on the case yet since it is currently still printing in my library as of July 19, 2024. I didn't re-adjust the screw holes during the design so some of the holes might have been cut off but it can be compensated with the hot inserts.  I will test it out once I have the printed case. The M2 screw holes on the PCB were plated to add enforcement.

-25mm trackball holder is integrated into the top case which is 13mm thick and sits flushed on the PCB.  Bottom case is 8.6mm thick.

-As for the 25mm trackball you will have to experiment as I previously mentioned in my other designs that POM ball works the best and Perixx balls might be a hit and miss.  You guys can experiment with different types of balls. Do so at your own risk.

-QMK source code was derived from **aki27's bally** as always. Code has been working stable for my previous designs with no issues.  I don't know much about manipulating the QMK source or converting it into Vial. If you have any questions please consult aki27 or QMK discord channel. Use at your own risk.


# Renders

![Screenshot 2024-07-18 at 2 15 16 PM](https://github.com/user-attachments/assets/c8e57288-f0ef-42b1-8ca9-1da98ff6ec2f)
![Screenshot 2024-07-18 at 1 29 56 PM](https://github.com/user-attachments/assets/e9599337-44e0-4aad-81ce-165b576d7f24)
![Screenshot 2024-07-18 at 1 29 26 PM](https://github.com/user-attachments/assets/06774130-c207-4c02-a907-a616656d4420)
![Screenshot 2024-07-18 at 1 29 07 PM](https://github.com/user-attachments/assets/a14c7bbb-fb10-478e-88ab-7f1686201684)
![Screenshot 2024-07-18 at 1 28 52 PM](https://github.com/user-attachments/assets/49d7b128-da0d-4545-b4d9-a0cfc9cbbd83)
![Screenshot 2024-07-18 at 12 15 42 PM](https://github.com/user-attachments/assets/15a2d6ca-3259-475d-8ccb-53fb76b430be)
![Screenshot 2024-07-18 at 11 09 03 AM](https://github.com/user-attachments/assets/b3419db6-417f-43d6-892b-643cef48fe00)
