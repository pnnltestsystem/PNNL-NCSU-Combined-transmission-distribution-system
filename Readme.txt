This repository contains the data of a standard test system to study T&D interactions due to high penetration of solar photovoltaic (PV) generation. The proposed test system can be used to study problems such as reverse power flows and voltage control issues as affected by variability from PV generation, in both T&D levels. The proposed test system combines the transmission IEEE 118 bus system, with the distribution IEEE 123-node feeder.

The information of each folder in this repository is given as follows:

Distribution Open DSS: 
-	5-minutes real and reactive power consumed by 91 loads and 5-minutes real power generated from PV at  91 load buses  in each month.

Transmission Gen_PV_Load data:
-	5-min PV generation data equivalent to 30% penetration (30% of peak load) was extracted and superimposed on PV generators placed at 54 load buses in the 118 bus system.

Transmission Power Flow Cases:
-	Raw files containing the power flow data (buses, loads, fixed shunt capacitors, generators, branches, transformers) in the base cases without PV and with PV placed at 54 load buses in the 118 bus system..

Unit Comittment Data to EOM:
-	Input Data: The input of the unit comittment and economic dispatch problem: load data, PV data, generator database.
-	UC&ED Solution: The solution of the unit comittment and economic dispatch problem for each generator in the 118 bus system with and without PV.
