# GPGN-590A-Final-Project-Instrumental-Designs_Proposed-Remote-Controled-Flowloop_-Proto-type-
# Final-Project-Instrumental-Designs-GPGN-590A

##Geoscience Motivation:
The primary project, taking place at the Edgar Mines facility, aims to measure and monitor slug flow via Distributed Acoustic Sensing (DAS). DAS, a recent trending technology being used for pipeline quality evaluation. This technology offers continuous, real-time, and remote acquisition of data.  DAS is also quick to mobilize and install. In this case, DAS is used along, as well as coiled about a pipe, whereby allowing the monitoring of strain-rate and track the response to the propagation of the slug flow. This type of flow is a common-occurrence/phenomena in multi-phase hydrocarbon production and transportation in both vertical, as well as inclined wellbores. Detection can prevent both unnecessary costs and allow the assessment of wellbore casing or pipeline integrity.  This study potentially will reshape multiple disciplines and applications, from oil and gas pipelines, various facilities, to civil engineering infrastructure projects. 
Fluid dynamics modeling is not always straight forward, there are many variables that impact the result, from: pipe diameter, inclination, curvature, material, any existing damage (dents or erosion), etc. So, by monitoring the movement of slug flow, the scientific community may be able to better constrain the aforementioned parameters.  The movement of slug flow provides an opportunity to better understand multiphase fluid flow within a pipe; from a perspective of how the flow influences acoustical and thermally on DAS response. In general, the composition of the slug flow consists of two parts: 1) the larger bubble has been named the Taylor bubble and is on the onset of the slug flow, followed by 2) a liquid slug, which takes on the appearance of a bubble curtain. The slug flow, travels at one velocity (group velocity), however the subparts (Talyor Bubble and Liquid Slug) each travel at different velocities (phase velocity). Along a pipeline trajectory, if there is any change to any pipeline parameters, from a physics perspective, the velocities will change and can be recorded by a Distributed Fiber Optic Sensing (DFOS) system.


## advantages: 
As for what we intend for class project and how it will bring value and both impact and help the research group(s) in Edgar Mines, is to build a mechanism whereby allowing the remote operation of the mines based experimental flow loop. The structure on site, fully mimics a real situation, a pipeline which is: curved, bent, inclined, buried, etc. Along this pipeline there exists control valves allowing the flow rate to be varied. There are also two flow meters, one for air and another for water. Also, along the loop there are multiple point-pressure and temperature measurements, as a reference for DAS response and slug flow movement. Due to the complexity of the daily operations on-site, strict facility time constraints, challenges to access the mine, economic impacts in terms of both travel-time and expense, and general safety concerns - there is a need for the ability for remote operation. Provided is a list of problems this instrumental solution will resolve: 
1)	Remote access allows alterations & testing even during nights, holidays or off-hours - when no personnel is on site or allowed within the Mines facility
2)	Provides an important health & safety solution for when weather is hazardous: 
a.	heavy snow – poor visibility
b.	icy roads
c.	extreme winds
3)	Reduction/removal of two-way travel-time, from Mines campus or other location to access the Mine and back
4)	Cost savings:
a.	Fuel costs 
b.	Wear and tear on vehicles
The initial project testing consists first to run various tests within the confines of the geoscience maker-space lab. Next the mechanism will be tested within the PE lab where a similar flow loop apparatus is already in place. Once those previous tests have proven reliable and robust, we will then test the remote mechanism in the ideal site of the Edgar Mines.

## Cost: 
$200-250

## Implementation plan (material check):
- [ ] Network (loop) of pvc pipes; straight pipes cut to various different lengths, joints, connectors 
- [ ] A water-filled reservoir tank
- [ ] A sufficiently powerful pump (based on the spec of the valve)
- [ ] Inclusion of those smart valves - driven/controlled by voltage signal; alternatively could be replaced the concept of servo control manual valves (only open and close)
- [ ] Necessary wiring (wiring diagrams as examples provided reference)
- [ ] Ample power (correctly positioned/wired within larger circuit, to ensure no impact on programmable logic board
- [ ] 8-switch relay board, ensured comment above covered; substituted for the need of shift register from proposal 
- [ ] Arduino Mega 2560 programmable logic board
- [ ] Arduino Ethernet/LAN Shield

## Possible additional elements: 
- [ ] Different type of smart valve for different flow regime
- [ ] More complicated loop design to include other fluid phases( i.e. air or mineral oil etc)
- [ ] More powerful pumps
- [ ] Quantitaive data acqusition tools such as (Distributed Acoustic Sensing, pressure gauges, flow meter etc.)


## Hardware Wiring Diagram:
Various existing designs are available online for accelerometers with different types of accelerometers. In this project, each of the different proposed accelerometers will be wired to communicate with analog-to-digital converter and send data to Arduino, as depicted above. As data is recorded it will be displayed on the LCD screen.

![Main station](/../main/images/main.png)
Main data station
![remote station](/../main/images/remote.png)
Remote data station

## Materials list:
- LIS3DH accelerometer (2) - $ 4.99/ea
![accel](/../main/Prototype photos/1-Arduino with LAN,CAT shield,cable.jpg) 
- LCD screen – $ 34.99​
![LCD](/../main/images/TFTLCD.jpg)
- Arduino UNO - $ 24.99
![UNO](/../main/images/UNO.jpeg)
- Arduino Mega 2560 - $ 39.99
![Mega](/../main/images/Mega.jpg)
- ADS1115(2) - $ 4.99/ea
![ADS](/../main/images/adc.jpg)
- Arduino W5100 ethernet shield - $ 20.99
![w5100](/../main/images/w5100.jpg)
- 32 GB microSD card - $ 9.99
![SD](/../main/images/SD.jpg)

