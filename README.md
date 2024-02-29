# Esphome_Watermeter

South France Watermeter model => IZAR module (Diehl IZAR RC 868 I G4)

Model capture next.

As you could see the watermeter ID is near to QR Code.

This Work use the great integration of Zibous => https://github.com/zibous/ha-watermeter

based on ESPHome + ESP32 (v4) + CC1101

Be carefull there is a big difference between IZAR RC 868 I R4 and G4 model 

it s know by watermeter bus as a DME07

The G4 Model use an encryption key without this one you can't decode G4 Values. 

But looking around the net i found a Pass key witch ran a lot of watermeter....

it is less talkative than the R4, so all the information from the integration of zibous does not come up.

Sensors translated from greman so ....
