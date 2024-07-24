# Cheapest-DIY-Onewheel
This is a quick guide to a fully DIY onewheel that I have designed that I believe is the best compromise between price and performance.
NOTE: if you live in the UK I will be offering a build service for all parts exept the battery.

This guide is quite advanced so be sure to read through the entire project before attempting to build your own board.
and sorry for waffley text of spelling errors i am just trying to explain the basic information
I will also be refering to Onewheel(tm) as the board throughout the guide.

Onewheels are dangerous especially if they are DIYed so build and ride at your own risk of injury or death!


I will be breaking this guide into 3 key sections Electronics, Structure and Software all of these aspects can be treated individually of eachother but are all essential to building a working board. 

Electronics:
Motor and Controller:
  In a board there are 3 primary electical components these being the controller the motor and the battery.
  Fortunatly a company called Spintend has made some of this easier by offering a kit designed for Onewheels there are a few to choose from I highly reccomend this kit 
  [](https://spintend.com/collections/diy-onewheel-parts-group/products/diy-onewheel-beast-power-pack7)   : only consider this if the price is bellow $330 as listed on 
  the website.

  but for those on a cheaper budget this kit may be more suitable: 
  [](https://spintend.com/collections/diy-onewheel-parts-group/products/diy-onewheel-balanced-board-pack2)   : ony consider this if the price is bellow $280 as listed on   the website.

  these kits take care of the motor and the controller and are the easiest way to acuire these two components however if they become unavailable the motor i reccomend is   the phub-188 these come in a few veritetes the best one would be the phub-188rk: [](https://www.peipeiscooter.com/10-inch-10x6-0-6-wide-tyre-strong-power-max-3000w-double-axles-scooter-hub-motor-wheel-phub-188rk.html)   : I havent personally tested this motor however the power setting offered does seem more suitable for the   
  application when ordering this motor ensure that the max voltage and power are selected.
  
  the controller I reccomend should always be purchaused from spintend the most important thing is ensuring that the vesc that is selected has a rated voltage around 15    - 20% greater than the planned max battery voltage (eg. if you are using a 75V battery the VESC should be able to handle atleat 90V but to be safe a 100V vesc would be   most suitable for this I reccoment using the UBOX 100V [](https://spintend.com/collections/esc-based-on-vesc/products/single-ubox-100v-100a-motor-controller-based-on-vesc) : this controller is high enough voltage and also contains an IMU sensor which is essential for the board to work.

  Footsensors:
   The kits contain foot sensors which will work well enought to get started with the board and can always be replaced later however if you decide to not go with the     
   kits I highly reccomend the sensors designed for car seat detection as these are the best bang for you buck sensors that I have personally tested and these are easy   
   to find at a low price on amazon. NOTE: I am working on an opensource solution that is much more reliable than this style of foot sensor i will include a link here 
   when it becomes available. 

Battery:
  this is the most difficult part of the build and there are a few different options. By far the cheapest option is building your own battery which while this seems like   like a daunting task it is much more achieveable than you might expect I would highly reccomend watching this video to fully understand the process of making your own 
  battery [](https://www.youtube.com/watch?v=tKg-jIrr_JE) you are looking to make an 18s pack ideally I would reccomend molicel P28A 18650 cells. for ideal range you 
  require making a 2p pack so in total you should purchause 36 cells to make the two packs. This guide doesnt focus on the battery so feel free to do aditional reasearch 
  into making or purchausing a suitable battery a key part of the battery that is essential there is a BMS this greatly reduces the risk of damage to the cells and fires.

Additional wireing:
  To complete this prodject you require a soldering iron and a few other components such as heat shrink and varius wire thicknesses and connectors such as bullet connectors and xt60 connectors.

