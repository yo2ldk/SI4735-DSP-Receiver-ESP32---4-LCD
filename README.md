# SI4735-DSP-Receiver-ESP32---4-LCD
Modified sketch for TFT LCD 4" controller ILI9488

  

                      All Band, all mode DSP Radio Receiver Si4735 with 4" TFT LCD driver ILI9488
                                            Modified by YO2LDK - Alexander -



           This sketch sketch is based on:
                                        the new version V3.5.of Gert Baak - PE0MGB V3.5;
                                        si4735 Library of Ricardo PU2CLR. Thanks for the very nice work.  
                                        V3.2.3  29-09-2021 Added Sprite buttons from Jim Yasuda.
                                        RDS Info text+Time & S-meter mod by Antonino Russo - IU4ALH 

                            Thank you all for hard work and many hours  to complete this nice radio project  ! 
           Also, this can be improved by someone with more experience than me, I'm just beginner; more to hardware oriented, than programming...   :)                    
                                     
    Updates:                                    
 
              -  Added  on screen the battery voltage (V) and have colour changed  (green full, yellow - middle, red - lower..so on 4 steps)
              -  The latest ino file "SI4735-DSP-Receiver-ESP32---4-LCD+RDS_info" is updated with the code from Antonino Russo -IU4ALH 
                   (please copy all files in the folder just new created )
  
  The radio is fully controlled by the (Touch)Screen and Rotary Encoder on ESP32 core
  This sketch uses the Rotary Encoder Class implementation from Ben Buxton (the source code is included
  together with this sketch).
  For the touch-screen the library TFT_eSPI is used.
  The configuration setup-file: _ILI9488 driver is also included.
  Maybe it have max two minor bugs, but is a start for everyone who need that.
             You are FREE to modify how you need it !
 

                          Thank you to all who make this project possible,
                       and for their hard work and many hours to write the code !!!


                          Please unzip the TFT_eSPI folder, inside of sketch folder !!
