# SolidWorks PCB / Altium biblioteka
KTU Elektros ir elektronikos fakulteto studentų sukurtu komponentų biblioteka.
 
[Templates](https://github.com/Aleksandrovas/KTU_Lib/tree/main/Templates) - schemų, komponentų sąrašo (BOM) šablonai

[SchLib](https://github.com/Aleksandrovas/KTU_Lib/tree/main/SchLib) - komponentų simboliai (schematic symbols)

[PcbLib](https://github.com/Aleksandrovas/KTU_Lib/tree/main/PcbLib) - komponentų topologiniai brėžiniai (footprints)


# Komponentų įvedimo taisyklės
Visi komponentai esantys bibliotekoje privalo turėti šiuos sutartinius parametrus:<br/>
• Manufacturer – gamintojas<br/>
• Manufacturer Part Number – gamintojo kodas<br/>
• Package – komponento korpuso tipas<br/>
• Supplier 1 – tiekėjas<br/>
• Supplier Part Number 1 – tiekėjo užsakymo kodas<br/>
• ComponentLink1Description - Datasheet<br/>
• ComponentLink1URL - nuoroda į techninę dokumentaciją<br/>


Priklausomai nuo komponento katerogijos įvedami papildomi parametrai<br/>

Kondensatoriai:<br/>
• Value
• Voltage
• Material
• Tolerance

