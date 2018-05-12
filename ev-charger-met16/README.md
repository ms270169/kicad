# ev-charger-met16

## History

### V0.1: Schematic and Layout finished

----------------------------------------------
 Topic          | Description
 :----          | :-----------
 Commit         | [3cf1186470543ce20f478d2e2e48a76af5a9076f](https://github.com/ManfredSteiner/kicad/tree/3cf1186470543ce20f478d2e2e48a76af5a9076f/ev-charger-met16)
 Status         | Design finished
 Manufactured   | No
 Tested         | No
 Issue 1       | 230V Voltage transformer module [ebay 232542976388](https://www.ebay.at/itm/232542976388) not working

#### Issues

1) Voltage transformer module does not work  
   * Wrong operation amplifier on module (OP07C instead of LM358)
   * PCB error on R3 (see [netlist-reverse-engieneered.jpg](problems/voltage-tranformer_ebay-232542976388/netlist-reverse-engieneered.jpg))

   Voltage between `OUT-GND` has only a amplitude maximum of 15mV arround 0V.
