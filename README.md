# Power-Supply-in-LAB

#### Hi,
 #### Shubh this side, I am here to give a bit of description about the project  that i made.
 
   👇  
 ![Power supply schematic](https://user-images.githubusercontent.com/79529647/119097876-157d5600-b9ca-11eb-91e4-b16aee57d14e.jpg)
 
 ##### Here is the schematic on which i worked. It clearly shows that the transformer is connected to the diodes and the Load.
 
 👆
 
 .                                    
 
   👇  
                                  ![IMG-20210308-WA0016](https://user-images.githubusercontent.com/79529647/119098730-fe8b3380-b9ca-11eb-9f58-70f6b69604f7.jpg)   
                               
   #### Now in this image we could see the actuall connection. The transformer is of 6v and 500ma (6-0-6v). 
   #### Transformer is connected so that we could step down the voltage coming from the main supply, the output of transformer will be 6v.
   #### Transformer passes the voltage to the diode so that it converts AC to DC. Then comes the resistor or load  for the output.
   
   👆                                                                                                           
   
   .                                                                    
   
    👇  
![IMG-20210308-WA0023](https://user-images.githubusercontent.com/79529647/119100721-19f73e00-b9cd-11eb-9d5e-7f9cb5b546e3.jpg)
   
   
#### According to this image, I took 2 wires and and first connected it to the multimeter for checking the output. 
####  After that i connected it to the DSO . As shown in the DSO i got DC as the output
#### although DC was not pure, which means compared to the battery it was'nt direct. Check the next image now.
👆                                                                   

.                                                                    
                                                                          
 👇 
 
  ![IMG-20210308-WA0020](https://user-images.githubusercontent.com/79529647/119103269-d05c2280-b9cf-11eb-9f16-59a5454cdaab.jpg)

 #### Now i added a Capacitor in the connection which is connected parallel to the resistor(i have'nt shown the capacitor in the schematic so, capacitor 
  #### is connected parallel to the resistane or load and its value is - 1000uf,45v)
 #### Now if we check our DSO we could se we are getting pulsatic output, which means the output is almost pure.
 #### How this happened, Capacitor's nature is to charge and discharge so as capacitor gets the input it charges but during discharging being of high value(1000uf)
 #### it takes miniseconds to discharge and starts charging again. This is why the curve in the DSO is approx straight but not full straight because of the time spent in discharging.

  
   👆   
   
  ### Now you can watch the video if you wish https://github.com/shubh0811/Power-Supply-in-LAB/blob/master/Video%20of%20the%20Project.mp4 .
   
   # Components used:
  #### 1)Transformer  6v and 500ma (6-0-6v).
  #### 2) Rsistor 1k ohm
  #### 3) Capacitor 1000uf,45v
  #### 4) Diodes 1N4007
  #### 5) Few jumper wires
   
   
   
   
   
   
   
