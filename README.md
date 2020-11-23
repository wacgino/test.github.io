This .md fiel is a summary of Power switch fundamentals of IGBT and SiC<br />
<br />
Difference between MOSFet, SiC MOSFET and IGBT<br />
<br />
  MOSFET and IGBT are based on Silicon material, SiC MOSFET based on SiC material.<br />
  Si MOSFET:<br />
    -operate in high frequency application<br />
    -low conduction loss(but not suitable for high current applications)<br />
  SiC MOSFET:<br />
    -higher bandgap energy and critical field breakdown voltage which is suitable for High-voltage operation<br />
    -higher thermal conductivity which requires less heatsinks<br />
    -lower switching loss<br />
  IGBT:<br />
    -has internal MOSFET driving BJT, low conduction loss(conductivity modulation), could be used for high current operation<br />
    -has reverse recovery phenomena(BJT), switching frequency applications(5KHz-20KHz)<br />

Drive Strength of power switch<br />
  -the drive strength of power switch is defined by the source and sink current capacility of gate drivers<br />
  -choosing the drive strength based on the gate charge of the power device<br />
  -the gate charge refers to the required amount of charge to charage and discharge the input capacitance<br />
  
