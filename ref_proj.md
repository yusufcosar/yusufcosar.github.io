## Portable Refrigerator Project

It is intended to keep drinks cold in the car, on the beach or in the far room of the house during summer days. For insulation, the inner surface is covered with 50 mm thick styrofoam, the outer surface is 1 mm stainless metal. The inner wall is made with 4 mm corrugated polycarbonate sheet.
The peltier is placed on the top of the refrigerator. Fans can be installed on both sides of the peltier to increase efficiency. The cables of the peltier, which works with 12 volts, can be connected directly to the car charging socket as well as operated from the domestic socket.
In order to prevent unnecessary energy consumption, a thermostat system is installed with arduino nano. When the inside of the cabinet drops to the determined temperature, the current supplied to the peltier is cut off.

### Peltier Effect

Peltier effect thermoelectric coolers and Peltier effect are used. It means that different current flows through the circuit consisting of conductors and besides generating irreversible Joule heat, endothermic and exothermic events will occur from the conductor junctions as the current direction is different. It was first discovered by JCA Peltier in 1834.
If it flows from conductor 1 to conductor 2 through the cable, the heat absorbed per unit area in conductor 1 is proportional to the current density passing through conductor 1 per unit time. Under the influence of an external electric field, the electrons move in direction. It brings some of the internal energy to the other end of the electric field.
When the current passing through different conductors passes through a loop, it irreversibly generates heat. In addition, since the direction of the current is different, heat absorption and heat release events will occur at different conductor junction points.
If current flows from terminal A with a large number of free electrons and to terminal B with a small number of free electrons, the temperature at terminal B will increase, otherwise the temperature at terminal B will decrease.

### Advantages
The main advantage of the Peltier effect is that it allows us to create cooling / heating devices with no moving parts and therefore less likely to fail compared to conventional coolers and heaters. They also require almost no maintenance.

### Disadvantages
The biggest disadvantage of the Peltier effect is that it is inefficient. The flowing current itself tends to generate a significant amount of heat, which adds to the overall heat dissipation. In large applications this results in an excessive amount of heat that needs attention. Typically, additional fans must be used to resolve this issue.
